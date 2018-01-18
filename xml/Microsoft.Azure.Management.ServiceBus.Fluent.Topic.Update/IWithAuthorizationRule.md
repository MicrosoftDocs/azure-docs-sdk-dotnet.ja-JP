<Type Name="IWithAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule">
  <TypeSignature Language="C#" Value="public interface IWithAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthorizationRule" />
  <TypeSignature Language="F#" Value="type IWithAuthorizationRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5eb1c-101">トピックへのアクセスの承認規則の追加を許可するトピックの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-101">The stage of the topic definition allowing to add an authorization rule for accessing the topic.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewListenRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewListenRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewListenRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule.WithNewListenRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewListenRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewListenRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewListenRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5eb1c-102">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-102">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="5eb1c-103">トピックにリッスンの承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-103">Creates a listen authorization rule for the topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5eb1c-104">トピックの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-104">Next stage of the topic update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewManageRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewManageRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewManageRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule.WithNewManageRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewManageRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewManageRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewManageRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5eb1c-105">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-105">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="5eb1c-106">トピックに管理承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-106">Creates a manage authorization rule for the topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5eb1c-107">トピックの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-107">Next stage of the topic update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSendRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewSendRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithNewSendRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule.WithNewSendRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSendRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSendRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewSendRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5eb1c-108">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-108">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="5eb1c-109">トピックに送信の承認規則を作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-109">Creates a send authorization rule for the topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5eb1c-110">トピックの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-110">Next stage of the topic update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAuthorizationRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutAuthorizationRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate WithoutAuthorizationRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IWithAuthorizationRule.WithoutAuthorizationRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAuthorizationRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAuthorizationRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate" Usage="iWithAuthorizationRule.WithoutAuthorizationRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5eb1c-111">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-111">Rule name.</span></span></param>
        <summary>
            <span data-ttu-id="5eb1c-112">トピックの承認規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-112">Removes an authorization rule for the topic.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5eb1c-113">トピックの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5eb1c-113">Next stage of the topic update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>