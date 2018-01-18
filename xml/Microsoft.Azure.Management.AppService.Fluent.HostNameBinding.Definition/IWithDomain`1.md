<Type Name="IWithDomain&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithDomain&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDomain&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomain`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithDomain`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomain(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDomain&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="318d2-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="318d2-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="318d2-102">指定するドメインを許可するホスト名バインド定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="318d2-102">The stage of a hostname binding definition allowing domain to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAzureManagedDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;ParentT&gt; WithAzureManagedDomain (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain`1&lt;!ParentT&gt; WithAzureManagedDomain(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithDomain`1.WithAzureManagedDomain(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAzureManagedDomain (domain As IAppServiceDomain) As IWithSubDomain(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAzureManagedDomain : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;'ParentT&gt;" Usage="iWithDomain.WithAzureManagedDomain domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="318d2-103">Azure から購入したドメイン。</span><span class="sxs-lookup"><span data-stu-id="318d2-103">The domain purchased from Azure.</span></span></param>
        <summary>
            <span data-ttu-id="318d2-104">Azure から購入したドメインにバインドします。</span><span class="sxs-lookup"><span data-stu-id="318d2-104">Binds to a domain purchased from Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="318d2-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="318d2-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;ParentT&gt; WithThirdPartyDomain (string domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain`1&lt;!ParentT&gt; WithThirdPartyDomain(string domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithDomain`1.WithThirdPartyDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyDomain (domain As String) As IWithSubDomain(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyDomain : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;'ParentT&gt;" Usage="iWithDomain.WithThirdPartyDomain domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IWithSubDomain&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="318d2-106">サード パーティ ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="318d2-106">The 3rd party domain name.</span></span></param>
        <summary>
            <span data-ttu-id="318d2-107">サードパーティのドメインにバインドします。</span><span class="sxs-lookup"><span data-stu-id="318d2-107">Binds to a 3rd party domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="318d2-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="318d2-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>