<Type Name="IWithPermissions&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPermissions&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPermissions`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPermissions(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPermissions&lt;'ParentT&gt; = interface" />
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
    <Member MemberName="AllowKeyAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowKeyAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowKeyAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowKeyAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyAllPermissions () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowKeyAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28a08-101">キーにアクセスする AD id のすべての権限を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-101">Allow all permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-102">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-102">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowKeyPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowKeyPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowKeyPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (ParamArray permissions As KeyPermissions()) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
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
        <param name="permissions"><span data-ttu-id="28a08-103">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="28a08-103">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="28a08-104">キーにアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-104">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-105">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-105">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowKeyPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowKeyPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowKeyPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowKeyPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowKeyPermissions (permissions As IList(Of KeyPermissions)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowKeyPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowKeyPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.KeyPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="28a08-106">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="28a08-106">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="28a08-107">キーにアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-107">Allow a list of permissions for the AD identity to access keys.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-108">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-108">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretAllPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowSecretAllPermissions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowSecretAllPermissions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowSecretAllPermissions" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretAllPermissions () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretAllPermissions : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowSecretAllPermissions " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="28a08-109">機密情報にアクセスする AD id のすべての権限を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-109">Allow all permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-110">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-110">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowSecretPermissions (params Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowSecretPermissions(class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowSecretPermissions(Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[])" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (ParamArray permissions As SecretPermissions()) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions[] -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
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
        <param name="permissions"><span data-ttu-id="28a08-111">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="28a08-111">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="28a08-112">機密情報にアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-112">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-113">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-113">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowSecretPermissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt; AllowSecretPermissions (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; AllowSecretPermissions(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithPermissions`1.AllowSecretPermissions(System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions})" />
      <MemberSignature Language="VB.NET" Value="Public Function AllowSecretPermissions (permissions As IList(Of SecretPermissions)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member AllowSecretPermissions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt; -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPermissions.AllowSecretPermissions permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Fluent.Models.SecretPermissions&gt;" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="28a08-114">権限の一覧が許可されるアクセス許可</span><span class="sxs-lookup"><span data-stu-id="28a08-114">permissions the list of permissions allowed</span></span></param>
        <summary>
            <span data-ttu-id="28a08-115">機密情報にアクセスする AD id の権限の一覧を許可します。</span><span class="sxs-lookup"><span data-stu-id="28a08-115">Allow a list of permissions for the AD identity to access secrets.</span></span>
            </summary>
        <returns><span data-ttu-id="28a08-116">アクセス ポリシーの定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="28a08-116">the next stage of access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>