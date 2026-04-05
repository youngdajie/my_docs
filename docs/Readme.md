---
pageLayout: home
home: true
config:
 -
    type: hero
    full: true
    effect: hyper-speed
    effectConfig:
      distortion: turbulentDistortion
      length: 400
      roadWidth: 10
      islandWidth: 2
      lanesPerRoad: 3
      fov: 90
      fovSpeedUp: 150
      speedUp: 2
      carLightsFade: 0.4
      totalSideLightSticks: 20
      lightPairsPerRoadWay: 40
      shoulderLinesWidthPercentage: 0.05
      brokenLinesWidthPercentage: 0.1
      brokenLinesLengthPercentage: 0.5
      lightStickWidth: [0.12, 0.5]
      lightStickHeight: [1.3, 1.7]
      movingAwaySpeed: [60, 80]
      movingCloserSpeed: [-120, -160]
      carLightsLength: [12, 80]
      carLightsRadius: [0.05, 0.14]
      carWidthPercentage: [0.3, 0.5]
      carShiftX: [-0.8, 0.8]
      carFloorSeparation: [0, 5]
      colors:
        roadColor: 0x080808
        islandColor: 0x0a0a0a
        background: 0x000000
        shoulderLines: 0x131318
        brokenLines: 0x131318
        leftCars: [0xd856bf, 0x6750a2, 0xc247ac]
        rightCars: [0x03b3c3, 0x0e5ea5, 0x324555]
        sticks: 0x03b3c3
    hero:
      name: 小杰说明书
      text: 杂七杂八
      tagline: 什么东西都往里塞
      actions:
        -
          theme: brand
          text: 快速开始
          link: /百宝箱/start/
        -
          theme: alt
          text: Github
          link: https://github.com/youngdajie
---