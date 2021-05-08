# Shiny 기초실습

* 강의와 실습은 [daattali/shiny-workshop-odsc2019](https://github.com/daattali/shiny-workshop-odsc2019) 를 이용합니다. 

* [Kaggle의 NBA 2018/19 시즌 스탯 데이터](https://www.kaggle.com/schmadam97/nba-regular-season-stats-20182019) 를 이용, Shiny app을 만드는 것이 목표입니다. 

* 최종 app은 [here](https://daattali.com/shiny/nba2018/) ([mirror](https://daattali.shinyapps.io/nba2018/)) 에서 미리 볼 수 있습니다

* [강의 슬라이드](https://jinseob2kim.github.io/shiny-workshop-odsc2019/), [original slide](https://github.com/daattali/shiny-workshop-odsc2019/raw/master/Shiny%20Workshop%20-%20ODSC%202019.pdf)


## 시작하기 전에

**Step 1:** https://rstudio.cloud 회원 가입

**Step 2:** https://rstudio.cloud/spaces/30306/join?access_code=s4hEiPXQF%2BjosPclQEzgTtR0mPWDuh7Dhr2O7wAg 들어가서 *"Join Space"* 클릭

**Step 3:** 위쪽 *"Projects"* 클릭 후, *"New Project"* 를 눌러 *"New Project from Git Repo"* 를 선택하세요. Repo 주소는  https://github.com/jinseob2kim/shiny-workshop-odsc2019 입니다.


![Step 3](https://i.imgur.com/nU5bbFL.png)

모든 강의자료는 RStudio cloud 에 들어 있습니다. 

---

개인 PC에서 실습을 원한다면 아래 Step을 따르세요.

**Optional Step 1:** 패키지 설치: `shiny`, `ggplot2`, `dplyr`, `DT`, `colourpicker`, `readr`. R에서 아래 명령어를 실행하세요.

```r
    install.packages(c("shiny", "ggplot2", "dplyr", "DT", "colourpicker", "readr")) 
```

**Optional Step 2:** https://github.com/jinseob2kim/shiny-workshop-odsc2019 에 들어간 후

**Optional Step 3:** 녹색 *"Clone or download"* 클릭 후 *"Download ZIP"* 을 눌러 자료를 다운받으세요. 
