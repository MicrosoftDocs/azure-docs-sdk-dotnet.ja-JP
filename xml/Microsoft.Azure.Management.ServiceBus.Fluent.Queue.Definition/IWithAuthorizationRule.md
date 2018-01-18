<Type Name="IWithAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithAuthorizationRule">
  <TypeSignature Language="C#" Value="public interface IWithAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthorizationRule" />
  <TypeSignature Language="F#" Value="type IWithAuthorizationRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="92aa6-101">キューへのアクセスの承認規則の追加を許可するキューの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="92aa6-101">The stage of the queue definition allowing to add an authorization rule for accessing the queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewListenRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewListenRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewListenRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithAuthorizationRule.WithNewListenRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewListenRule (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewListenRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithAuthorizationRule.WithNewListenRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="92aa6-102">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="92aa6-102">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="92aa6-103">キューにリッスンの承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="92aa6-103">Creates a listen authorization rule for the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="92aa6-104">キュー定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="92aa6-104">Next stage of the queue definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewManageRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewManageRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewManageRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithAuthorizationRule.WithNewManageRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewManageRule (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewManageRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithAuthorizationRule.WithNewManageRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="92aa6-105">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="92aa6-105">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="92aa6-106">キューの管理の承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="92aa6-106">Creates a manage authorization rule for the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="92aa6-107">キュー定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="92aa6-107">Next stage of the queue definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSendRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewSendRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithNewSendRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithAuthorizationRule.WithNewSendRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSendRule (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSendRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithAuthorizationRule.WithNewSendRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="92aa6-108">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="92aa6-108">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="92aa6-109">キューの送信の承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="92aa6-109">Creates a send authorization rule for the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="92aa6-110">キュー定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="92aa6-110">Next stage of the queue definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>