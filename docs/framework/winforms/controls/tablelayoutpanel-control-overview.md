---
title: TableLayoutPanel 컨트롤 개요
ms.date: 03/30/2017
f1_keywords:
- TableLayoutPanel
helpviewer_keywords:
- controls [Windows Forms], resizing
- resizable controls [Windows Forms]
- Windows Forms controls, proportional resizing
- Windows Forms, proportional resizing of controls
- layout [Windows Forms], TableLayoutPanel control
- TableLayoutPanel control [Windows Forms], about TableLayoutPanel control
ms.assetid: 337661c8-61cb-44ee-93e0-3662bddec327
ms.openlocfilehash: be7ef4055d809349fe97a3d48e29158c5449576b
ms.sourcegitcommit: 3c1c3ba79895335ff3737934e39372555ca7d6d0
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/06/2018
ms.locfileid: "43855805"
---
# <a name="tablelayoutpanel-control-overview"></a>TableLayoutPanel 컨트롤 개요
<xref:System.Windows.Forms.TableLayoutPanel> 컨트롤은 해당 내용을 표에 정렬합니다. 레이아웃이 디자인 타임과 런타임에 모두 수행되므로 응용 프로그램 환경이 변경되면 동적으로 변경될 수 있습니다. 따라서 패널의 컨트롤이 비례적으로 크기를 조정할 수 있으므로 지역화로 인한 부모 컨트롤 크기 조정이나 텍스트 길이 변경과 같은 변경 내용에 응답할 수 있습니다.  
  
 Windows Forms 컨트롤은 <xref:System.Windows.Forms.TableLayoutPanel>의 다른 인스턴스를 포함하여 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤의 자식일 수 있습니다. 따라서 런타임에 변경 내용에 맞게 조정되는 정교한 레이아웃을 생성할 수 있습니다.  
  
 <xref:System.Windows.Forms.TableLayoutPanel.RowCount%2A>, <xref:System.Windows.Forms.TableLayoutPanel.ColumnCount%2A> 및 <xref:System.Windows.Forms.TableLayoutPanel.GrowStyle%2A> 속성의 값에 따라 새 컨트롤을 추가할 때 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤이 이를 수용하기 위해 확장될 수 있습니다. <xref:System.Windows.Forms.TableLayoutPanel.RowCount%2A> 또는 <xref:System.Windows.Forms.TableLayoutPanel.ColumnCount%2A> 속성의 값을 0으로 설정하면 <xref:System.Windows.Forms.TableLayoutPanel>이 해당 방향으로 바인딩되지 않습니다.  
  
 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤이 자식 컨트롤로 가득 찬 후에 확장 방향(가로 또는 세로)을 제어할 수도 있습니다. 기본적으로 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤은 행을 추가하여 아래로 확장됩니다.  
  
 기본 동작과 다르게 동작하는 행과 열을 원하는 경우 <xref:System.Windows.Forms.TableLayoutPanel.RowStyles%2A> 및 <xref:System.Windows.Forms.TableLayoutPanel.ColumnStyles%2A> 속성을 사용하여 행과 열의 속성을 제어할 수 있습니다. 행 또는 열의 속성을 개별적으로 설정할 수 있습니다.  
  
 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤은 자식 컨트롤에 `Cell`, `Column`, `Row`, `ColumnSpan` 및 `RowSpan` 속성을 추가합니다.  
  
 자식 컨트롤의 `ColumnSpan` 또는 `RowSpan` 속성을 설정하여 <xref:System.Windows.Forms.TableLayoutPanel> 컨트롤에 셀을 병합할 수 있습니다.  
  
1.  [방법: TableLayoutPanel 컨트롤의 컨트롤 맞춤 및 늘이기](how-to-align-and-stretch-a-control-in-a-tablelayoutpanel-control.md)  
  
2.  [방법: TableLayoutPanel 컨트롤에서 행과 열 확장](how-to-span-rows-and-columns-in-a-tablelayoutpanel-control.md)  
  
3.  [방법: TableLayoutPanel 컨트롤에서 열과 행 편집](how-to-edit-columns-and-rows-in-a-tablelayoutpanel-control.md)  
  
4.  [연습: TableLayoutPanel을 사용하여 Windows Forms에서 컨트롤 정렬](https://msdn.microsoft.com/library/w4yc3e8c\(v=vs.110\))  
  
## <a name="see-also"></a>참고 항목  
 <xref:System.Windows.Forms.FlowLayoutPanel>  
 <xref:System.Windows.Forms.TableLayoutSettings>  
 [방법: 지역화에 적합한 Windows Forms 레이아웃 디자인](../../../../docs/framework/winforms/controls/how-to-design-a-windows-forms-layout-that-responds-well-to-localization.md)  
 [방법: 데이터를 입력할 수 있는 크기 조정 가능한 Windows Form 만들기](../../../../docs/framework/winforms/controls/how-to-create-a-resizable-windows-form-for-data-entry.md)  
 [TableLayoutPanel 컨트롤에 대한 모범 사례](../../../../docs/framework/winforms/controls/best-practices-for-the-tablelayoutpanel-control.md)
