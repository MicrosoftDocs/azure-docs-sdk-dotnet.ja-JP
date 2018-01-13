<Type Name="IWithIPAddress" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPAddress" />
  <TypeSignature Language="F#" Value="type IWithIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サーバーの開始 IP アドレスを設定するファイアウォール ルールの SQL 定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddress.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate" Usage="iWithIPAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">IPv4 形式で IP アドレスです。</param>
        <summary>
            SQL server のファイアウォール規則の終了 IP アドレスを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>