<Type Name="IWithCustomDomain" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain">
  <TypeSignature Language="C#" Value="public interface IWithCustomDomain" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCustomDomain" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCustomDomain" />
  <TypeSignature Language="F#" Value="type IWithCustomDomain = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0ca53-101">パラメーターを変更できるように、ストレージ アカウントの更新段階です。</span><span class="sxs-lookup"><span data-stu-id="0ca53-101">A storage account update stage allowing to change the parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain customDomain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
      </Parameters>
      <Docs>
        <param name="customDomain"><span data-ttu-id="0ca53-102">ストレージ アカウントに割り当てられているユーザーのドメイン。</span><span class="sxs-lookup"><span data-stu-id="0ca53-102">The user domain assigned to the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="0ca53-103">ストレージ アカウントに割り当てられたユーザー ドメインを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ca53-103">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0ca53-104">ストレージ アカウントの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0ca53-104">The next stage of storage account update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0ca53-105">カスタム ドメイン名は、CNAME ソース。</span><span class="sxs-lookup"><span data-stu-id="0ca53-105">The custom domain name, which is the CNAME source.</span></span></param>
        <summary>
            <span data-ttu-id="0ca53-106">ストレージ アカウントに割り当てられたユーザー ドメインを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ca53-106">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0ca53-107">ストレージ アカウントの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0ca53-107">The next stage of storage account update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain (string name, bool useSubDomain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithCustomDomain(string name, bool useSubDomain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithCustomDomain.WithCustomDomain(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (name As String, useSubDomain As Boolean) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string * bool -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithCustomDomain.WithCustomDomain (name, useSubDomain)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="useSubDomain" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0ca53-108">カスタム ドメイン名は、CNAME ソース。</span><span class="sxs-lookup"><span data-stu-id="0ca53-108">The custom domain name, which is the CNAME source.</span></span></param>
        <param name="useSubDomain"><span data-ttu-id="0ca53-109">間接 CName 検証が有効になっているかどうか。</span><span class="sxs-lookup"><span data-stu-id="0ca53-109">Whether indirect CName validation is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="0ca53-110">ストレージ アカウントに割り当てられたユーザー ドメインを指定します。</span><span class="sxs-lookup"><span data-stu-id="0ca53-110">Specifies the user domain assigned to the storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0ca53-111">ストレージ アカウントの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0ca53-111">The next stage of storage account update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>