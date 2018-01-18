<Type Name="IWithHostNameBinding&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameBinding&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameBinding`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1" />
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
    <typeparam name="FluentT"><span data-ttu-id="5d770-101">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="5d770-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5d770-102">Web アプリのステージでは、許可するホスト名のバインドを設定するを更新します。</span><span class="sxs-lookup"><span data-stu-id="5d770-102">The stage of the web app update allowing host name binding to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineHostnameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineHostnameBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.DefineHostnameBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineHostnameBinding () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineHostnameBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithHostNameBinding.DefineHostnameBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d770-103">新しいホスト名のバインドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="5d770-103">Starts the definition of a new host name binding.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5d770-104">ホスト名バインドの更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="5d770-104">The first stage of a hostname binding update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedHostnameBindings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithManagedHostnameBindings (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithManagedHostnameBindings(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithManagedHostnameBindings(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithManagedHostnameBindings (domain As IAppServiceDomain, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedHostnameBindings : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithManagedHostnameBindings (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
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
        <param name="domain"><span data-ttu-id="5d770-105">Azure では、ドメインを管理します。</span><span class="sxs-lookup"><span data-stu-id="5d770-105">The Azure managed domain.</span></span></param>
        <param name="hostnames"><span data-ttu-id="5d770-106">サブドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="5d770-106">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="5d770-107">Azure のホスト名のリストを定義する管理対象ドメイン。</span><span class="sxs-lookup"><span data-stu-id="5d770-107">Defines a list of host names of an Azure managed domain.</span></span> <span data-ttu-id="5d770-108">ルート レベルのドメインを除く CNAME を DNS レコードの種類が既定値 ("です。</span><span class="sxs-lookup"><span data-stu-id="5d770-108">The DNS record type is defaulted to be CNAME except for the root level domain (".</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5d770-109">Web アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5d770-109">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutHostnameBinding (string hostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutHostnameBinding(string hostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithoutHostnameBinding(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutHostnameBinding (hostname As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutHostnameBinding : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithoutHostnameBinding hostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="5d770-110">バインドを解除するホスト名です。</span><span class="sxs-lookup"><span data-stu-id="5d770-110">The hostname to unbind.</span></span></param>
        <summary>
            <span data-ttu-id="5d770-111">Web アプリからホスト名をバインド解除します。</span><span class="sxs-lookup"><span data-stu-id="5d770-111">Unbinds a hostname from the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5d770-112">Web アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5d770-112">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithThirdPartyHostnameBinding (string domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithThirdPartyHostnameBinding(string domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithThirdPartyHostnameBinding(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyHostnameBinding (domain As String, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyHostnameBinding : string * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithThirdPartyHostnameBinding (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
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
        <param name="domain"><span data-ttu-id="5d770-113">外部のドメイン名。</span><span class="sxs-lookup"><span data-stu-id="5d770-113">The external domain name.</span></span></param>
        <param name="hostnames"><span data-ttu-id="5d770-114">サブドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="5d770-114">The list of sub-domains.</span></span></param>
        <summary>
            <span data-ttu-id="5d770-115">外部から購入したドメインのホスト名の一覧を定義します。</span><span class="sxs-lookup"><span data-stu-id="5d770-115">Defines a list of host names of an externally purchased domain.</span></span> <span data-ttu-id="5d770-116">ホスト名は、web アプリを指す手の形の前に構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5d770-116">The hostnames must be configured before hand to point to the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5d770-117">Web アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5d770-117">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>