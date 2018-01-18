<Type Name="IWithAccessPolicy" FullName="Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithAccessPolicy">
  <TypeSignature Language="C#" Value="public interface IWithAccessPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAccessPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithAccessPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAccessPolicy" />
  <TypeSignature Language="F#" Value="type IWithAccessPolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bec44-101">アクセス ポリシーをアタッチする資格情報コンテナーの定義。</span><span class="sxs-lookup"><span data-stu-id="bec44-101">A key vault definition allowing access policies to be attached.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Definition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate&gt; DefineAccessPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Definition.IBlank`1&lt;class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate&gt; DefineAccessPolicy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithAccessPolicy.DefineAccessPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAccessPolicy () As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAccessPolicy : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Definition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate&gt;" Usage="iWithAccessPolicy.DefineAccessPolicy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.AccessPolicy.Definition.IBlank&lt;Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bec44-102">この key vault に追加する新しいアクセス ポリシーの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="bec44-102">Begins the definition of a new access policy to be added to this key vault.</span></span>
            </summary>
        <returns><span data-ttu-id="bec44-103">アクセス ポリシーの定義の最初の段階</span><span class="sxs-lookup"><span data-stu-id="bec44-103">the first stage of the access policy definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate WithAccessPolicy (Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate WithAccessPolicy(class Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy accessPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithAccessPolicy.WithAccessPolicy(Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAccessPolicy (accessPolicy As IAccessPolicy) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithAccessPolicy : Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate" Usage="iWithAccessPolicy.WithAccessPolicy accessPolicy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessPolicy" Type="Microsoft.Azure.Management.KeyVault.Fluent.IAccessPolicy" />
      </Parameters>
      <Docs>
        <param name="accessPolicy"><span data-ttu-id="bec44-104">accessPolicy、既存のアクセス ポリシー</span><span class="sxs-lookup"><span data-stu-id="bec44-104">accessPolicy the existing access policy</span></span></param>
        <summary>
            <span data-ttu-id="bec44-105">既存のアクセス ポリシーをアタッチします。</span><span class="sxs-lookup"><span data-stu-id="bec44-105">Attach an existing access policy.</span></span>
            </summary>
        <returns><span data-ttu-id="bec44-106">資格情報コンテナー定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="bec44-106">the next stage of key vault definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithEmptyAccessPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate WithEmptyAccessPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate WithEmptyAccessPolicy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithAccessPolicy.WithEmptyAccessPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Function WithEmptyAccessPolicy () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithEmptyAccessPolicy : unit -&gt; Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate" Usage="iWithAccessPolicy.WithEmptyAccessPolicy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Fluent.Vault.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bec44-107">アクセス ポリシーはアタッチされません。</span><span class="sxs-lookup"><span data-stu-id="bec44-107">Attach no access policy.</span></span>
            </summary>
        <returns><span data-ttu-id="bec44-108">資格情報コンテナー定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="bec44-108">the next stage of key vault definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>