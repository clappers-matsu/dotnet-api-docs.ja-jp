---
ms.openlocfilehash: 483f2c83f4d55aad694ba713c787972178b19e5e
ms.sourcegitcommit: 1bb00d2f4343e73ae8d58668f02297a3cf10a4c1
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/15/2019
ms.locfileid: "63872453"
---

ただし、**String.Format** メソッドの呼び出し時に、呼び出す特定のオーバーロードに焦点を当てる必要はありません。 代わりに、1 つ以上の書式項目を含む、[複合書式指定文字列](~/docs/standard/base-types/composite-formatting.md)を指定してメソッドを呼び出すことができます。 各書式項目を数値インデックスに割り当てます。最初のインデックスは 0 から始まります。 最初の文字列だけでなく、メソッド呼び出しには、インデックス値と同じ数の追加引数が必要です。 たとえば、書式項目のインデックスが 0 と 1 の文字列には 2 個の引数が必要です。インデックスが 0 から 5 の場合は、6 個の引数が必要です。 その後、言語コンパイラは、**String.Format** メソッドの特定のオーバーロードに対するメソッド呼び出しを解決します。   
 
**String.Format** メソッドの使用に関する詳細なドキュメントについては、[String.Format メソッドの概要](#Starting)と[呼び出すメソッド](#FTaskList)に関するトピックを参照してください。    
