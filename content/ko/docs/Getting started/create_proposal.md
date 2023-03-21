---
title: "제안하기"
linkTitle: "제안하기"
weight: 5
---

## 제안 리스트
DAO 토큰을 보유하여 DAO 참여 자격을 얻으면 DAO 내에서 제안을 하거나 제안에 투표하여 참여할 수 있습니다. Home 화면에서는 현재 제출된 제안들을 확인할 수 있습니다.

![](/docs/images/list.png)

## 새로운 제안하기
여러분은 DAO에서 언제든지 새로운 제안을 만들고 제출할 수 있습니다. 단, 여러분이 속한 DAO의 규칙에 따라 제안 제출시에는 일정량 이상의 토큰을 필요로 합니다. 

### Community Proposal 제안하기
DAO에서 구성원들과 함께 의견을 나누고 토론할 제안을 제출합니다. 여기서는 새로운 투자를 하기 위해 제안을 만들었습니다. 제목과 제안에 대한 설명을 작성한 다음, 제안에 대한 이해를 도울 수 있는 첨부파일을 추가하십시오. 제안을 다 작성하고 제출하면 트랜잭션 서명창이 나옵니다. ByFactory 사용자들의 트랜잭션 수수료 비용은 무료입니다.

![](/docs/images/community_proposal1.png)

작성한 제안이 제출된 것을 확인할 수 있습니다.
![](/docs/images/list2.png)


### Configuration Proposal 제안하기
DAO의 속성을 바꾸고 싶다면 Configuration Proposal을 제출하십시오. 현재 ByFactory에서 기본적으로 제공하는 정책은 [아래](#제안의-종류)에서 확인하실 수 있습니다. 여기서는 제안 제출시 필요 토큰 수량을 50으로 조정하는 예시를 보여주고 있습니다. 이 제안이 통과된다면 제안 제출시 필요 토큰 수량이 현재 100에서 50으로 변경됩니다. Configuration Proposal은 **제안이 통과되면 그 즉시 컨트랙트에 수치가 변경되어 적용됩니다.**

![](/docs/images/configuration_proposal1.png)

작성한 제안이 제출된 것을 확인할 수 있습니다.
![](/docs/images/list3.png)

## 제안의 종류
현재 ByFactory의 제안에는 Community Proposal과 Configuration Proposal 두 종류가 있으며 각 역할은 아래와 같습니다.

| 구분            | 역할           |
|-------------------|-----------------|
| Community Proposal | DAO의 운영을 위해 사용하는 커뮤니티 제안</br> DAO의 목적에 따라 여러가지 타입이 존재함</br> |
| Configuration Proposal | DAO가 가진 정책의 관리를 위해 사용하는 제안</br>기존 정책 변경 또는 새로운 정책을 제안할 수 있음</br> 제안 통과시 컨트랙트를 통해 즉시 반영됨 |

### Community Proposal 타입 예시
현재 Community Proposal의 타입은 펀드 DAO에 맞춰져 있습니다. 추후 Proposal 타입은 DAO의 목적에 따라 추가하거나 변경할 수 있습니다.
* 새로운 펀드 제안
* 새로운 딜 제안
* 투자 심사 제안
* 기타

### Configuration Proposal 정책 예시
* 제안 제출시 필요 토큰 수량
* 투표시 필요 토큰 수량
* 지갑당 최대 투표 파워(Vote Power)
* 한번에 제출 가능한 최대 투표 파워
* 제안 통과에 필요한 투표 파워
* 제안 통과에 필요한 최소 투표자 수
