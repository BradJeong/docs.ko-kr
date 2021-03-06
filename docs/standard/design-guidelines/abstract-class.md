---
title: 추상 클래스 디자인
ms.date: 03/30/2017
ms.technology: dotnet-standard
helpviewer_keywords:
- type design guidelines, abstract classes
- abstract classes, design guidelines
- class library design guidelines [.NET Framework], classes
- classes [.NET Framework], abstract
- classes [.NET Framework], design guidelines
- type design guidelines, classes
ms.assetid: d3646e6d-5c1f-4922-8fb0-ec5effb30d60
author: rpetrusha
ms.author: ronpet
ms.openlocfilehash: c5b9dacc4995a126e1ee3f6062dca796194d4882
ms.sourcegitcommit: dfb2a100cfb4d3902c042f17b3204f49bc7635e7
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/20/2018
ms.locfileid: "46493492"
---
# <a name="abstract-class-design"></a>추상 클래스 디자인
**X DO NOT** 추상 형식에 public 또는 protected 내부 생성자를 정의 합니다.  
  
 생성자는 사용자가 형식의 인스턴스를 만들어야 하는 경우에 공용 이어야 합니다. 추상 형식의 인스턴스를 만들 수 없으므로, public 생성자를 사용 하는 추상 형식이 아닌 경우 올바르게 설계 및 사용자에 게 잘못 된  
  
 **✓ DO** 추상 클래스에는 protected 또는 내부 생성자를 정의 합니다.  
  
 생성자는 protected 생성자는 좀 더 자주 및 하위 형식을 만들면 자체 초기화 작업을 수행 하는 기본 클래스를 사용 하는 단순히 합니다.  
  
 추상 클래스를 정의 하는 어셈블리 클래스의 구체적 구현 제한 하는 내부 생성자를 사용할 수 있습니다.  
  
 **✓ DO** 배송 된 각 추상 클래스에서 상속 하는 구체적인 형식이 하나 이상 제공 합니다.  
  
 이 사용이 하면 추상 클래스의 디자인 유효성 검사를 수행 합니다. 예를 들어 <xref:System.IO.FileStream?displayProperty=nameWithType> 구현인는 <xref:System.IO.Stream?displayProperty=nameWithType> 추상 클래스입니다.  
  
 *Portions © 2005, 2009 Microsoft Corporation. 모든 권리 보유.*  
  
 *Pearson Education, Inc의 동의로 재인쇄. 출처: [Framework Design Guidelines: Conventions, Idioms, and Patterns for Reusable .NET Libraries, 2nd Edition](https://www.informit.com/store/framework-design-guidelines-conventions-idioms-and-9780321545619) 작성자: Krzysztof Cwalina 및 Brad Abrams, 출판 정보: Oct 22, 2008 by Addison-Wesley Professional as part of the Microsoft Windows Development Series.*  
  
## <a name="see-also"></a>참고자료

- [형식 디자인 지침](../../../docs/standard/design-guidelines/type.md)  
- [프레임워크 디자인 지침](../../../docs/standard/design-guidelines/index.md)
