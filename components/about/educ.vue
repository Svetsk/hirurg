<script setup>

</script>

<template>
  <div class="container">
    <div class="flex justify-between items-start mt-[134px] nm">
      <div class="flex flex-col">
        <div class="flex items-center gap-[24px]">
          <div class="line"></div>
          <ui-elements-title title="Образование" />
        </div>
          <div class="flex flex-wrap justify-between gap-y-[52px] ttex">
            <div class="flex gap-[40px] tex">
              <div>
                <div>
                  <h3 class="text-[25px] font-[500]">Диплом</h3>
                  <p class="text-[15px] font-[500] text-[#BBBBBB]">2006-2010</p>
                </div>
                <p class="max-w-[456px] text-[20px] font-[500]">
                  Кропоткинский медицинский колледж. Лечебный факультет, специальность «Лечебное дело».
                </p>
              </div>
              <div>
                <div>
                  <h3 class="text-[25px] font-[500]">Диплом</h3>
                  <p class="text-[15px] font-[500] text-[#BBBBBB]">2016-2018</p>
                </div>
                <p class="max-w-[456px] text-[20px] font-[500]">
                  Кубанский государственный медицинский университет,<br>г. Краснодар, ординатура по онкологии<br>с курсом торакальной хирургии.
                </p>
              </div>
            </div>
            <div class="flex gap-[40px] tex">
              <div>
                <div>
                  <h3 class="text-[25px] font-[500]">Диплом</h3>
                  <p class="text-[15px] font-[500] text-[#BBBBBB]">2010-2016</p>
                </div>
                <p class="max-w-[456px] text-[20px] font-[500]">
                  Кубанский государственный медицинский университет, г. Краснодар,<br>Лечебный факультет, специальность «Лечебное дело».
                </p>
              </div>
              <div>
                <div>
                  <h3 class="text-[25px] font-[500]">Диплом</h3>
                  <p class="text-[15px] font-[500] text-[#BBBBBB]">2019-2021</p>
                </div>
                <p class="max-w-[456px] text-[20px] font-[500]">
                  Военно-медицинская академия имени<br>С. М. Кирова в городе Санкт-Петербург, ординатура по пластической хирургии.
                </p>
              </div>
            </div>
        </div>
      </div>
      <div class="wrp">
        <div class="wrrp">
          <div class="flex items-center">
            <p class="text-[70px] font-[600] textx">30+</p>
            <p class="text-[20px] font-[500] textxx w-[305px]">стажировок, конгрессов, конференций, симпозиумов</p>
          </div>
          <div class="educ">
            <nuxt-img src="/image/about/educ.png" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.wrp{
  border-radius: 40px;
  border: 1px solid #FFF;
  background: rgba(255, 255, 255, 0.20);
  backdrop-filter: blur(30px);
  margin-left: 50px;
}
.wrrp{
  display: flex;
  flex-direction: column;
  gap: 40px;
  padding: 42px 80px;
}
.educ{
  width: 500px;
  height: 360px;
}
@media screen and (max-width: 1440px) {
  .tex{
    & > div > p{
      font-size: 18px;
    }
  }
}
@media screen and (max-width: 1024px) {
  .nm{
    flex-direction: column;
  }
}
@media screen and (max-width: 768px) {
  .nm{
    flex-wrap: wrap;
  }
  .ttex{
    padding-bottom: 76px;
  }
  .tex{
    flex-wrap: wrap;
  }
  .wrp{
    margin: 0 auto;
  }
}
@media screen and (max-width: 425px) {
  .wrrp{
    gap: 28px;
    padding: 25px 20px;
    align-items: center;
  }
  .textx{
    font-size: 60px;
  }
  .textxx{
    font-size: 14px;
    max-width: 220px;
  }
  .educ{
    width: 320px;
    height: 240px;
  }
}
@media screen and (max-width: 390px) {
  .wrrp{
    gap: 16px;
    padding: 25px 20px;
    align-items: center;
  }
  .textx{
    font-size: 60px;
  }
  .textxx{
    font-size: 12px;
    max-width: 200px;
  }
  .educ{
    width: 300px;
    height: 220px;
  }
}
</style>