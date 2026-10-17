# Blender cascaduer live link for ARP(Auto Rig Pro)
blender와 cascaduer 라이브 연동을 위한 글

TeamGadget-JP님의 TeamGadget Universal Real-Time Sync System의 GHEB를 fork해서 arp에 사용가능하게 만들었습니다.
TeamGadget-JP 감사합니다

<br>


*현재 arp에서 리깅할때 뼈 구조를 unreal 5와 spine을 straight 모드로 바꾸고 사용하여야 합니다. 


<시연영상>
https://youtu.be/SZ_MpMnoEFE

<사용방법>
https://github.com/TeamGadget-JP/UNIVERSAL_REAL-TIME_SYNC_SYSTEM
에서 최신버전의 G-HUB, GHEC 2개를 다운 후 적용후

GHEB 블렌더 애드온만 이 애드온으로 바꿔 이용하면 됩니다. 



<img width="291" height="540" alt="스크린샷 2026-10-13 202859" src="https://github.com/user-attachments/assets/04cdb39c-ff5b-4a90-a50f-5184199f4a85" />

<원리>
캐스캐이더의 좌표값을 블렌더로 넘긴후 리타게팅 하는 과정을 GPT-6.1로 코딩하였습니다.
이론상 모든 리타게팅 가능 본을 라이브로 사용할 수 있습니다. *만약 ARP 말고 다른 리그 본을 이용하고 있다면, GHEB만 수정하면 되므로 GPT, CLAUDE등으로 이 부분만 바꿔달라고 요청하세요.


2026/10/17 update

블렌더, 캐스캐이더, ghub fork용으로 prop, 카메라 추가했습니다
prop은 블렌더에서 본, 메쉬 리그한후 본을 넘기면 같이 넘겨지고
카메라는 캐스캐이더에서 블렌더로 실시간 연동됩니다.

<img width="287" height="1053" alt="스크린샷 2026-10-17 133445" src="https://github.com/user-attachments/assets/bcb21860-c2e1-49ea-969c-3ccc4b9c131d" />
<img width="295" height="1063" alt="스크린샷 2026-10-17 133430" src="https://github.com/user-attachments/assets/9269026a-bac3-4039-a44f-7f8f79b0ba3c" />


JP
blenderとcascaduerのライブ連携のための記事

TeamGadget-JP様のTeamGadget Universal Real-Time Sync SystemのGHEBをforkし、arpで使用できるようにいたしました。
TeamGadget-JP ありがとうございます

*現在のarpでリギングする際は、骨構造をunreal 5とspineをstraightモードに切り替えて使用しなければなりません。 

<デモ動画>
https://youtu.be/SZ_MpMnoEFE

<使用方法>
https://github.com/TeamGadget-JP/UNIVERSAL_REAL-TIME_SYNC_SYSTEM
GHEBアドオンだけを差し替えたアドオンとしてご利用いただけます。

## 감사합니다 
https://github.com/TeamGadget-JP/UNIVERSAL_REAL-TIME_SYNC_SYSTEM










