<Type Name="OperationKind" FullName="Microsoft.Azure.Documents.OperationKind">
  <TypeSignature Language="C#" Value="public enum OperationKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OperationKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.OperationKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum OperationKind" />
  <TypeSignature Language="F#" Value="type OperationKind = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="e9954-101">これらは、操作の種類のリソース バージョンの競合が発生しました。</span><span class="sxs-lookup"><span data-stu-id="e9954-101">These are the operation types resulted in a version conflict on a resource.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="e9954-102">取得する非同期操作中に、バージョン競合が発生したときに、<see cref="T:Microsoft.Azure.Documents.Conflict" />インスタンスにより、どのリソースと操作 caause を判断する競合。</span><span class="sxs-lookup"><span data-stu-id="e9954-102">When a version conflict occurs during an async operation, retrieving the <see cref="T:Microsoft.Azure.Documents.Conflict" /> instance will allow you to determine which resource and operation caause the conflict.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="Create" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.OperationKind Create = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.OperationKind.Create" />
      <MemberSignature Language="VB.NET" Value="Create" />
      <MemberSignature Language="F#" Value="Create = 1" Usage="Microsoft.Azure.Documents.OperationKind.Create" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9954-103">作成操作。</span><span class="sxs-lookup"><span data-stu-id="e9954-103">A create operation.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="Delete" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.OperationKind Delete = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.OperationKind.Delete" />
      <MemberSignature Language="VB.NET" Value="Delete" />
      <MemberSignature Language="F#" Value="Delete = 3" Usage="Microsoft.Azure.Documents.OperationKind.Delete" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9954-104">削除操作。</span><span class="sxs-lookup"><span data-stu-id="e9954-104">A delete operation.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.OperationKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.OperationKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="Microsoft.Azure.Documents.OperationKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9954-105">無効な操作です。</span><span class="sxs-lookup"><span data-stu-id="e9954-105">An invalid operation.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="Read" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.OperationKind Read = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.OperationKind.Read" />
      <MemberSignature Language="VB.NET" Value="Read" />
      <MemberSignature Language="F#" Value="Read = 4" Usage="Microsoft.Azure.Documents.OperationKind.Read" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This item is obsolete as it does not apply to Conflict.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9954-106">この操作は、競合には適用されません。</span><span class="sxs-lookup"><span data-stu-id="e9954-106">This operation does not apply to Conflict.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="Replace" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.OperationKind Replace = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.OperationKind.Replace" />
      <MemberSignature Language="VB.NET" Value="Replace" />
      <MemberSignature Language="F#" Value="Replace = 2" Usage="Microsoft.Azure.Documents.OperationKind.Replace" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.OperationKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="e9954-107">置換操作。</span><span class="sxs-lookup"><span data-stu-id="e9954-107">An replace operation.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>