## 아시아나 항공 기상 예보팀

### Introducing Forecasting Model Overviews

아시아나 항공 기상그룹에서 공항기상 지원을 위해 사용하는 NWP(Numerical Weather Prediction)모델들에 대해서 소개하고 어떻게 실제 활용하고 있는지에 대해서 공유하고자 하여 작성하였습니다.



##### NWP Model Category

**1. UM (Unified Model)**

**2. GFS (Global Forecast System)**

**3. ECMWF (European Centre for Mid-Range Weather Forecasts)**

**4. HRRR (High Resolution Rapid Refresh)**

**5. RAP (RAPid Refresh)**

**6. NAM (North American Mesoscale Model)**


#### 1. UM 모델
* [방재기상정보시스템](http://afso.kma.go.kr/)
![KMA](/images/UM_1.jpg)
* 활용 가능 지역 - 한국, 중국, 일본

 : 예보 모델 결과물은 1일 4회(0000Z, 0600Z, 1200Z, 1800Z)에 발표가 되며, 기준 시간 + 3~4 Hour 이후에 결과물이 해당 페이지에 갱신된다.

 * UM전구 - 예보 간격 1일 4회
 
    > 0000Z 1200Z에 발표되는 예보자료에는 +288 Hour 까지 예상도 자료를 볼 수 있다.

    > 0600Z 1800Z에 발표되는 예보자료에는 +84 Hour 까지 예상도 자료를 볼 수 있다.
    
    ![UM전구](/images/GDAPS_1.jpg)
    
 * UM지역 - 예보 간격 1일 4회
    
 * 국지모델 -예보 간격 1일 4회

    > 한반도 지역의 경우 아래와 같이 국지모델까지 활용 가능하며, 해당 모델 시간 간격은 1Hour 해상도가 좋기 때문에
    
    > 국개 각 공항별로 국지적인 기상정보 지원이 가능하다. 하지만  지원 가능한 시간대가 제한적이다.
    
    ![국지모델](/images/GDAPS_L_1.jpg)


#### 2. GFS 모델
* [Model Analyses And Guidance - NCEP Central Operatios](http://mag.ncep.noaa.gov/)
![GFS](/images/NCEP_1.jpg)
* 활용 가능 지역
 * 전지구

