# Capstone2023_SmartPot
Arduino Code for Smart Pot

## 목차
  - [목차](#목차)
  - [Ⅰ. 프로젝트 실행 동기 및 목적](#ⅰ-프로젝트-실행-동기-및-목적)
  - [Ⅱ. 이론적 배경(기존 사례)](#ⅱ-이론적-배경기존-사례)
  - [Ⅲ. 프로젝트 방법 및 과정](#ⅲ-프로젝트-방법-및-과정)
    - [1. 개발 순서 구상](#1-개발-순서-구상)
      - [1) 프로그램에 포함되어야 할 기능](#1-프로그램에-포함되어야-할-기능)
      - [2) 사용자 진행 순서도](#2-사용자-진행-순서도)
    - [2. 사용 기술 선정](#2-사용-기술-선정)
    - [3. 데이터베이스 설계](#3-데이터베이스-설계)
    - [4. 기능 구현](#4-기능-구현)

## Ⅰ. 프로젝트 실행 동기 및 목적
식물을 키우는 것이 어렵거나 번거로운 경우가 있습니다. 스마트 화분은 이러한 문제를 해결해주고, 사람들이 식물을 더욱 쉽게 키울 수 있도록 도와줍니다.

스마트 화분은 식물의 생장에 필요한 온도, 습도, 빛 등의 환경을 자동으로 조절해줄 수 있습니다. 이를 통해 식물이 더욱 건강하게 자라고, 사람들이 더욱 편리하게 식물을 관리할 수 있습니다.

스마트 화분은 IoT(Internet of Things) 기술을 활용하여 스마트폰이나 컴퓨터를 통해 실시간으로 식물의 상태를 확인할 수 있도록 합니다. 이를 통해 사용자들은 언제 어디서든 식물을 관리할 수 있게 됩니다.

마지막으로, 스마트 화분을 만드는 것은 기술적인 도전과 공학적인 문제를 해결하는데 도움이 됩니다. 이를 통해 새로운 기술과 제품을 개발하는데 기여할 수 있습니다.

이러한 이유들을 바탕으로 스마트 화분 프로젝트를 실행하는 것은 사람들의 삶에 긍정적인 영향을 미치고, 동시에 기술적인 발전에도 기여할 수 있기 때문입니다.

## Ⅱ. 이론적 배경(기존 사례)
자동화 기술 및 IoT 기술
스마트 화분은 식물의 환경을 자동으로 제어하기 위한 기술이 필요합니다. 이를 위해 자동화 기술과 IoT 기술이 사용됩니다. 자동화 기술은 식물의 환경 요소를 모니터링하고, 그에 따라 물과 영양분을 자동으로 공급하며, 조명과 습도를 조절하는 등의 작업을 수행합니다. 또한, IoT 기술을 통해 사용자는 스마트폰이나 컴퓨터를 통해 식물의 상태를 실시간으로 확인하고 관리할 수 있습니다.

하이드로포닉스 기술
스마트 화분에는 하이드로포닉스 기술이 사용될 수 있습니다. 하이드로포닉스는 식물을 물 대신에 액체 양분을 이용하여 기르는 방법으로, 물의 낭비를 줄이고 식물의 성장을 촉진하는 장점이 있습니다. 또한, 하이드로포닉스 기술을 적용한 화분은 자동화 기술과 쉽게 결합될 수 있어 더욱 효율적인 식물 관리가 가능합니다.

스마트 화분 제품
최근에는 다양한 제조업체들이 스마트 화분 제품을 출시하고 있습니다. 대표적인 제품으로는 "Parrot Pot"이 있습니다. 이 제품은 습도, 온도, 토양 수분 등의 센서를 이용하여 식물의 상태를 모니터링하고, 스마트폰 앱을 통해 실시간으로 확인할 수 있습니다. 또한, 자동으로 물을 공급하고 조명을 조절하여 식물이 건강하게 자라도록 도와줍니다.

## Ⅲ. 프로젝트 방법 및 과정
### 1. 개발 순서 구상
![화면 캡처 2022-03-29 215427](https://user-images.githubusercontent.com/81201101/160825996-27719cfc-e088-47ed-8a85-4ed912721970.png)


#### 1) 프로그램에 포함되어야 할 기능
센서 기능: 스마트 화분은 식물의 상태를 모니터링하기 위해 온도, 습도, 토양 수분 등의 센서를 사용해야 합니다. 이러한 센서를 이용하여 식물의 상태를 실시간으로 모니터링하고, 그에 따라 물과 영양분을 자동으로 공급하거나, 조명과 습도를 조절해야 합니다.

자동화 기능: 스마트 화분은 자동화 기능이 필요합니다. 센서 데이터를 분석하여 식물의 상태에 따라 물과 영양분을 자동으로 공급하며, 조명과 습도를 조절하는 등의 작업을 수행해야 합니다.

모바일 애플리케이션: 사용자는 스마트폰 앱을 통해 식물의 상태를 실시간으로 모니터링하고, 식물의 성장 과정을 확인할 수 있어야 합니다. 또한, 앱을 통해 스마트 화분의 설정을 변경하거나, 식물에 대한 조언 및 권장 사항을 제공하는 기능도 필요합니다.

#### 2) 사용자 진행 순서도
![qq](https://user-images.githubusercontent.com/81201101/160827186-babae781-5313-4112-83e6-ba668feaecc1.png)

### 2. 사용 기술 선정




### 3. 데이터베이스 설계
![KakaoTalk_20230406_194022498](https://user-images.githubusercontent.com/129836696/230354919-11629b30-563a-4693-baaf-9b24358ebdd6.png)


### 4. 기능 구현
