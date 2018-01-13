<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConnectionString(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithConnectionString&lt;'FluentT&gt; = interface" />
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
            設定への接続文字列を許可する、web アプリ定義段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name">接続文字列の名前。</param>
        <param name="value">接続文字列の値。</param>
        <param name="type">接続文字列の種類。</param>
        <summary>
            Web アプリを接続文字列を追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name">接続文字列の名前。</param>
        <param name="value">接続文字列の値。</param>
        <param name="type">接続文字列の種類。</param>
        <summary>
            Web アプリを接続文字列を追加します。 この接続文字列は、デプロイ スロットをスワップした後もスワップされます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>