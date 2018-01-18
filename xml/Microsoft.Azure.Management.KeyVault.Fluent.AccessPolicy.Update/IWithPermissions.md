<Type Name="IWithPermissions" FullName="Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions">
  <TypeSignature Language="C#" Value="public interface IWithPermissions" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPermissions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPermissions" />
  <TypeSignature Language="F#" Value="type IWithPermissions = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a93ab-101">アクセス ポリシーは、ステージを追加または削除するアクセス許可を更新します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-101">The access policy update stage allowing permissions to be added or removed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AllowKeyAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a93ab-102">キーにアクセスする AD id のすべての権限を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-102">Allow all permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-103">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-103">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (ParamArray permissions As KeyPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-104">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="a93ab-104">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-105">キーにアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-105">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-106">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-106">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowKeyPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowKeyPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (permissions As IList(Of KeyPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-107">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="a93ab-107">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-108">キーにアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-108">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-109">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-109">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a93ab-110">機密情報にアクセスする AD id のすべての権限を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-110">Allow all permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-111">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-111">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (ParamArray permissions As SecretPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-112">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="a93ab-112">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-113">機密情報にアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-113">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-114">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-114">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate AllowSecretPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.AllowSecretPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (permissions As IList(Of SecretPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-115">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="a93ab-115">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-116">機密情報にアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-116">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-117">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-117">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a93ab-118">キーにアクセスする AD id のすべての権限を取り消します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-118">Revoke all permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-119">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-119">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyPermissions (ParamArray permissions As KeyPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-120">アクセス許可を失効させる権限の一覧</span><span class="sxs-lookup"><span data-stu-id="a93ab-120">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-121">キーにアクセスする AD id の権限の一覧を取り消してください。</span><span class="sxs-lookup"><span data-stu-id="a93ab-121">Revoke a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-122">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-122">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowKeyPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowKeyPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowKeyPermissions (permissions As IList(Of KeyPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowKeyPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-123">アクセス許可を失効させる権限の一覧</span><span class="sxs-lookup"><span data-stu-id="a93ab-123">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-124">キーにアクセスする AD id の権限の一覧を取り消してください。</span><span class="sxs-lookup"><span data-stu-id="a93ab-124">Revoke a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-125">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-125">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretAllPermissions () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a93ab-126">機密情報にアクセスする AD id のすべての権限を取り消します。</span><span class="sxs-lookup"><span data-stu-id="a93ab-126">Revoke all permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-127">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-127">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretPermissions (ParamArray permissions As SecretPermissions()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-128">アクセス許可を失効させる権限の一覧</span><span class="sxs-lookup"><span data-stu-id="a93ab-128">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-129">機密情報にアクセスする AD id の権限の一覧を取り消してください。</span><span class="sxs-lookup"><span data-stu-id="a93ab-129">Revoke a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-130">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-130">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisallowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate DisallowSecretPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IWithPermissions.DisallowSecretPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function DisallowSecretPermissions (permissions As IList(Of SecretPermissions)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member DisallowSecretPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate" Usage="iWithPermissions.DisallowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="a93ab-131">アクセス許可を失効させる権限の一覧</span><span class="sxs-lookup"><span data-stu-id="a93ab-131">permissions the list of permissions to revoke</span></span></param>
        <summary>
            <span data-ttu-id="a93ab-132">機密情報にアクセスする AD id の権限の一覧を取り消してください。</span><span class="sxs-lookup"><span data-stu-id="a93ab-132">Revoke a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="a93ab-133">アクセス ポリシーの更新の次のステージ</span><span class="sxs-lookup"><span data-stu-id="a93ab-133">the next stage of access policy update</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>