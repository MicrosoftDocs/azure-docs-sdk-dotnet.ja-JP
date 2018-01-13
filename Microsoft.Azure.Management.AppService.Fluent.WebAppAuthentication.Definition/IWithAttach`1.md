<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider&lt;ParentT&gt;, Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithExternalRedirectUrls&lt;ParentT&gt;, Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithExternalRedirectUrls`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithAuthenticationProvider(Of ParentT), IWithExternalRedirectUrls(Of ParentT), IWithTokenStore(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithAuthenticationProvider&lt;'ParentT&gt;&#xA;    interface IWithTokenStore&lt;'ParentT&gt;&#xA;    interface IWithExternalRedirectUrls&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAuthenticationProvider&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithExternalRedirectUrls&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            Web アプリの認証の定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、または WithAttach.attach() を使用して、親 web アプリケーションの定義に、web アプリの認証の定義をアタッチできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>