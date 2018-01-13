<Type Name="CompletionMode" FullName="System.Fabric.CompletionMode">
  <TypeSignature Language="C#" Value="public enum CompletionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed CompletionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CompletionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum CompletionMode" />
  <TypeSignature Language="F#" Value="type CompletionMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="bcf05-101">これは、API が完了する必要がありますを示すために使用される列挙型です。</span><span class="sxs-lookup"><span data-stu-id="bcf05-101">This is an enum used to indicate when the API should complete.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="bcf05-102">値は、操作の要求が行われるとき、または要求された操作が完了したときに、API が完了する必要があるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="bcf05-102">The values indicate whether the API should complete when the request for the operation is done or when the requested operation has completed.</span></span> <span data-ttu-id="bcf05-103">たとえば、ノードを再起動する要求をすぐに、要求が承諾されると、または API では、ノードが再起動されることを確認できます完了でした。</span><span class="sxs-lookup"><span data-stu-id="bcf05-103">For example,  a request to restart a node  could complete as soon the request is accepted or when the API can verify that the node has restarted.</span></span> <span data-ttu-id="bcf05-104">実際の認証は、使用されている API に依存します。</span><span class="sxs-lookup"><span data-stu-id="bcf05-104">The actual verification depends upon the API being used.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="DoNotVerify">
      <MemberSignature Language="C#" Value="DoNotVerify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode DoNotVerify = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.DoNotVerify" />
      <MemberSignature Language="VB.NET" Value="DoNotVerify" />
      <MemberSignature Language="F#" Value="DoNotVerify = 1" Usage="System.Fabric.CompletionMode.DoNotVerify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcf05-105">アクションの完了を確認しません。</span><span class="sxs-lookup"><span data-stu-id="bcf05-105">Do not verify the completion of the action.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.CompletionMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcf05-106">入力候補モードでは、有効な値はありません。</span><span class="sxs-lookup"><span data-stu-id="bcf05-106">Completion mode does not have a valid value.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="Verify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Verify = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Verify" />
      <MemberSignature Language="VB.NET" Value="Verify" />
      <MemberSignature Language="F#" Value="Verify = 2" Usage="System.Fabric.CompletionMode.Verify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcf05-107">アクションの完了を確認します。</span><span class="sxs-lookup"><span data-stu-id="bcf05-107">Verify the completion of the action.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>