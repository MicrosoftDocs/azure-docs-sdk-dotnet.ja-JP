<Type Name="IWithHostNameBinding&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithHostNameBinding&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameBinding&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameBinding`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithHostNameBinding`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostNameBinding(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithHostNameBinding&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="1b335-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="1b335-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="1b335-102">ホストの名前を指定するバインドを許可する、web アプリ定義段階です。</span><span class="sxs-lookup"><span data-stu-id="1b335-102">A web app definition stage allowing host name binding to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt; DefineHostnameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt;&gt; DefineHostnameBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithHostNameBinding`1.DefineHostnameBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineHostnameBinding () As IBlank(Of IWithCreate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineHostnameBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;&gt;" Usage="iWithHostNameBinding.DefineHostnameBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.Definition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1b335-103">新しいホスト名のバインドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="1b335-103">Starts the definition of a new host name binding.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1b335-104">ホスト名バインド定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="1b335-104">The first stage of a hostname binding definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedHostnameBindings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithManagedHostnameBindings (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithManagedHostnameBindings(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithHostNameBinding`1.WithManagedHostnameBindings(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithManagedHostnameBindings (domain As IAppServiceDomain, ParamArray hostnames As String()) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedHostnameBindings : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithManagedHostnameBindings (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="1b335-105">Azure では、ドメインを管理します。</span><span class="sxs-lookup"><span data-stu-id="1b335-105">The Azure managed domain.</span></span></param>
        <param name="hostnames"><span data-ttu-id="1b335-106">サブドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="1b335-106">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="1b335-107">Azure のホスト名のリストを定義する管理対象ドメイン。</span><span class="sxs-lookup"><span data-stu-id="1b335-107">Defines a list of host names of an Azure managed domain.</span></span> <span data-ttu-id="1b335-108">ルート レベルのドメインを除く CNAME を DNS レコードの種類が既定値 ("です。</span><span class="sxs-lookup"><span data-stu-id="1b335-108">The DNS record type is defaulted to be CNAME except for the root level domain (".</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1b335-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1b335-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithThirdPartyHostnameBinding (string domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithThirdPartyHostnameBinding(string domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithHostNameBinding`1.WithThirdPartyHostnameBinding(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyHostnameBinding (domain As String, ParamArray hostnames As String()) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyHostnameBinding : string * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithThirdPartyHostnameBinding (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain"><span data-ttu-id="1b335-110">外部のドメイン名。</span><span class="sxs-lookup"><span data-stu-id="1b335-110">The external domain name.</span></span></param>
        <param name="hostnames"><span data-ttu-id="1b335-111">サブドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="1b335-111">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="1b335-112">外部から購入したドメインのホスト名の一覧を定義します。</span><span class="sxs-lookup"><span data-stu-id="1b335-112">Defines a list of host names of an externally purchased domain.</span></span> <span data-ttu-id="1b335-113">ホスト名は、web アプリを指す手の形の前に構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b335-113">The hostnames must be configured before hand to point to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1b335-114">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="1b335-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>