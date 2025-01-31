## iBlood app Expo cli로 react-native build(21-03-19 추가)

❍ Expo cli 설치
```
npm install -g expo-cli
```

❍ .expo 파일을 package.json과 동일 위치에 맞추기

❍ package.json과 동일 위치에 npm install

❍ 안 될시
```
npm install --legacy-peer-deps
```
❍ expo go로 아이폰 device에서 보려고 할 때 
- 그냥 하면 "react-native": "https://github.com/expo/react-native/archive/sdk-36.0.1.tar.gz",
버전 낮아서 실행 안 됨
- package.json에서 버전만 고치고 npm install 해도 계속 충돌 남!!
```
expo update
```
로 해야 depengencies 맞춰서 install 되고 package.json 알아서 바뀜!!




# dribbble2react
We're transforming [Dribbble](https://dribbble.com/) designs to React / React-Native code

Don't miss the updates when I release new apps, just subscribe to our [React-UI-Kit newsletter](https://react-ui-kit.com/).

Checkout the new React-Native marketplace for ready-to-use UI code [react-ui-kit.com](https://react-ui-kit.com/)

| Project | Expo | Preview | Screens | Estimation | Status |
| ------ | ------ | :------: | :------: | :------: | :------: |
| [Camping Spots Finder App](https://dribbble.com/shots/5765449-Camping-Spots-Finder-App-Day-364-365-Project365/attachments/1243964) | [View Snack](https://snack.expo.io/@react-ui-kit/camping-spots-finder-app) | <img src="https://cdn.dribbble.com/users/386883/screenshots/5765449/attachments/1243964/30122018-design.png" width="120" /> | 2 | 5 hours | :white_check_mark: |
| [Velocity UI Kit](https://www.invisionapp.com/inside-design/design-resources/design-system-dashboard-ui-kit/) | [View Snack](https://snack.expo.io/@react-ui-kit/velocity-ui-kit) | <img src="https://s3.amazonaws.com/www-inside-design/uploads/2019/01/velocity-gallery-md-4.png" width="120" /> | 10-12 | ~35 hours | :hammer_and_wrench: |
| [Car Parking Finder App](https://dribbble.com/shots/5361780-Car-Parking-Finder-App-Day-280-365-Project365/attachments/1162528) | [View Snack](https://snack.expo.io/@react-ui-kit/car-parking-finder-app) | <img src="https://cdn.dribbble.com/users/386883/screenshots/5361780/attachments/1162528/07102018-design.png" width="120" /> | 1-2 | ~4 hours | :white_check_mark: |
| [Travel Article App UI](https://dribbble.com/shots/5717917-Travel-Article-Application/attachments/1234851) | [View Snack](https://snack.expo.io/@react-ui-kit/travel-article-app-ui) | <img src="https://cdn.dribbble.com/users/1631607/screenshots/5717917/attachments/1234851/____-1.0.png" width="120" /> | 2 | ~5 hours | :white_check_mark: |
| [Smart Home App UI](https://dribbble.com/shots/4585243-Smart-Home-App-Ui/attachments/1036679) | [View Snack](https://snack.expo.io/@react-ui-kit/smart-home-app-ui) | <img src="https://cdn.dribbble.com/users/968354/screenshots/4585243/attachments/1036679/smart_home_app_ui_attachment.png" width="120" /> | 2 | ~4 hours | :white_check_mark: |
| [Blood Donation App](https://dribbble.com/shots/5755829-Blood-Donation-App-Day-361-365-Project365/attachments/1242361) | [View Snack](https://snack.expo.io/@react-ui-kit/blood-donation-app) | <img src="https://cdn.dribbble.com/users/386883/screenshots/5755829/attachments/1242361/27122018-design.png" width="120" /> | 2 | ~2 hours | :white_check_mark: |
| [Driving AI assistant](https://dribbble.com/shots/4560198-Driving-AI-assistant/attachments/1031428) | [View Snack](https://snack.expo.io/@react-ui-kit/driving-ai-assistant) | <img src="https://cdn.dribbble.com/users/389060/screenshots/4560198/attachments/1031428/expanded.png" width="120" /> | 5 | ~15 hours | :white_check_mark: | 
| [Plant App](https://dribbble.com/shots/4569970-Plant-Freebie-2-Dribbble-Invites/attachments/1033490) | [View Snack](https://snack.expo.io/@react-ui-kit/plant-app) | <img src="https://cdn.dribbble.com/users/1002086/screenshots/4569970/attachments/1033490/hd.png" width="120" /> | 6 | ~20 hours | :white_check_mark: |
| [VPN App](https://project365.design/2018/10/05/day-278-vpn-mobile-app-ui-kit-sketch-freebie/) | [View Snack](https://expo.io/snacks/@react-ui-kit) | <img src="https://project365.design/wp-content/uploads/2018/10/05102018-design.png" width="120" /> | 2 | ~2 hours | :white_check_mark: |
| [Your app](https://github.com/react-ui-kit/dribbble2react/issues/new?assignees=&labels=&template=feature_request.md&title=) | - | Your design | - | ~ hours | :point_left::hammer_and_wrench: |





## Contributors
<a href="https://opencollective.com/dribbble2react"><img src="https://opencollective.com/dribbble2react/individuals.svg?width=890"></a>
