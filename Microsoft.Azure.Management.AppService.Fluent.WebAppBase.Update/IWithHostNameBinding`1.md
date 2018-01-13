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
    <typeparam name="FluentT">リソースの型。</typeparam>
    <summary>
            Web アプリのステージでは、許可するホスト名のバインドを設定するを更新します。
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
            新しいホスト名のバインドの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ホスト名バインドの更新プログラムの最初の段階です。</return>
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
        <param name="domain">Azure では、ドメインを管理します。</param>
        <param name="hostnames">サブドメインの一覧。</param>
        <summary>
            Azure のホスト名のリストを定義する管理対象ドメイン。 ルート レベルのドメインを除く CNAME を DNS レコードの種類が既定値 ("です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新プログラムの次のステージ。</return>
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
        <param name="hostname">バインドを解除するホスト名です。</param>
        <summary>
            Web アプリからホスト名をバインド解除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新プログラムの次のステージ。</return>
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
        <param name="domain">外部のドメイン名。</param>
        <param name="hostnames">サブドメインの一覧。</param>
        <summary>
            外部から購入したドメインのホスト名の一覧を定義します。 ホスト名は、web アプリを指す手の形の前に構成する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>