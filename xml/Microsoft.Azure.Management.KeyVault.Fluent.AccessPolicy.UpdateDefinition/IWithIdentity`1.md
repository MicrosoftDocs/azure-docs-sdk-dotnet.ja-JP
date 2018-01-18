<Type Name="IWithIdentity&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithIdentity&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdentity`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdentity(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithIdentity&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ForGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForGroup (Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup group);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForGroup(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForGroup(Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForGroup (group As IActiveDirectoryGroup) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForGroup : Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForGroup group" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="group" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryGroup" />
      </Parameters>
      <Docs>
        <param name="group"><span data-ttu-id="e858f-101">AD グループ オブジェクトをグループ化します。</span><span class="sxs-lookup"><span data-stu-id="e858f-101">group the AD group object</span></span></param>
        <summary>
            <span data-ttu-id="e858f-102">このアクセス ポリシーは、Active Directory グループを指定します。</span><span class="sxs-lookup"><span data-stu-id="e858f-102">Specifies the Active Directory group this access policy is for.</span></span>
            </summary>
        <returns><span data-ttu-id="e858f-103">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="e858f-103">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForObjectId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForObjectId (Guid objectId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForObjectId(valuetype System.Guid objectId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForObjectId(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForObjectId (objectId As Guid) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForObjectId : Guid -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForObjectId objectId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="objectId"><span data-ttu-id="e858f-104">AD id の objectId オブジェクト ID</span><span class="sxs-lookup"><span data-stu-id="e858f-104">objectId the object ID of the AD identity</span></span></param>
        <summary>
            <span data-ttu-id="e858f-105">このアクセス ポリシーは、Active Directory id のオブジェクト ID を指定します。</span><span class="sxs-lookup"><span data-stu-id="e858f-105">Specifies the object ID of the Active Directory identity this access policy is for.</span></span>
            </summary>
        <returns><span data-ttu-id="e858f-106">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="e858f-106">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForServicePrincipal">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForServicePrincipal (Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal servicePrincipal);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForServicePrincipal(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal servicePrincipal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForServicePrincipal(Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForServicePrincipal (servicePrincipal As IServicePrincipal) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForServicePrincipal : Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForServicePrincipal servicePrincipal" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="servicePrincipal" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IServicePrincipal" />
      </Parameters>
      <Docs>
        <param name="servicePrincipal"><span data-ttu-id="e858f-107">servicePrincipal AD サービス プリンシパル オブジェクト</span><span class="sxs-lookup"><span data-stu-id="e858f-107">servicePrincipal the AD service principal object</span></span></param>
        <summary>
            <span data-ttu-id="e858f-108">このアクセス ポリシーは、Active Directory サービス プリンシパルを指定します。</span><span class="sxs-lookup"><span data-stu-id="e858f-108">Specifies the Active Directory service principal this access policy is for.</span></span>
            </summary>
        <returns><span data-ttu-id="e858f-109">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="e858f-109">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForServicePrincipal">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForServicePrincipal (string servicePrincipalName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForServicePrincipal(string servicePrincipalName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForServicePrincipal(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForServicePrincipal (servicePrincipalName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForServicePrincipal : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForServicePrincipal servicePrincipalName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="servicePrincipalName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePrincipalName"><span data-ttu-id="e858f-110">servicePrincipalName AD ユーザーのサービス プリンシパル名</span><span class="sxs-lookup"><span data-stu-id="e858f-110">servicePrincipalName the service principal name of the AD user</span></span></param>
        <summary>
            <span data-ttu-id="e858f-111">このアクセス ポリシーは、Active Directory サービス プリンシパルを指定します。</span><span class="sxs-lookup"><span data-stu-id="e858f-111">Specifies the Active Directory service principal this access policy is for.</span></span>
            </summary>
        <returns><span data-ttu-id="e858f-112">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="e858f-112">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForUser (Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForUser(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForUser(Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForUser (user As IActiveDirectoryUser) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForUser : Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryUser -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForUser user" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IActiveDirectoryUser" />
      </Parameters>
      <Docs>
        <param name="user">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; ForUser (string userPrincipalName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ForUser(string userPrincipalName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithIdentity`1.ForUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForUser (userPrincipalName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ForUser : string -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdentity.ForUser userPrincipalName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userPrincipalName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userPrincipalName"><span data-ttu-id="e858f-113">userPrincipalName AD ユーザーのユーザー プリンシパル名</span><span class="sxs-lookup"><span data-stu-id="e858f-113">userPrincipalName the user principal name of the AD user</span></span></param>
        <summary>
            <span data-ttu-id="e858f-114">このアクセス ポリシーは、Active Directory ユーザーを指定します。</span><span class="sxs-lookup"><span data-stu-id="e858f-114">Specifies the Active Directory user this access policy is for.</span></span>
            </summary>
        <returns><span data-ttu-id="e858f-115">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="e858f-115">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>