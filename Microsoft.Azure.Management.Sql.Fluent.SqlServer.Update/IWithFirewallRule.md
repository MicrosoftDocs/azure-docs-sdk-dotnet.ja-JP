<Type Name="IWithFirewallRule" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule">
  <TypeSignature Language="C#" Value="public interface IWithFirewallRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFirewallRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFirewallRule" />
  <TypeSignature Language="F#" Value="type IWithFirewallRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ファイアウォール規則を指定するための SQL Server 定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule.WithNewFirewallRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithFirewallRule.WithNewFirewallRule ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">ファイアウォール ルールの IP アドレスです。</param>
        <summary>
            SQL Server の新しいファイアウォール規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server 更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule (string startIPAddress, string endIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule(string startIPAddress, string endIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule.WithNewFirewallRule(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (startIPAddress As String, endIPAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithFirewallRule.WithNewFirewallRule (startIPAddress, endIPAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startIPAddress" Type="System.String" />
        <Parameter Name="endIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIPAddress">ファイアウォール ルールの IP アドレスを開始します。</param>
        <param name="endIPAddress">ファイアウォール ルールの IP アドレスです。</param>
        <summary>
            SQL Server の新しいファイアウォール規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server 更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule (string startIPAddress, string endIPAddress, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithNewFirewallRule(string startIPAddress, string endIPAddress, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule.WithNewFirewallRule(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (startIPAddress As String, endIPAddress As String, firewallRuleName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithFirewallRule.WithNewFirewallRule (startIPAddress, endIPAddress, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startIPAddress" Type="System.String" />
        <Parameter Name="endIPAddress" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIPAddress">ファイアウォール ルールの IP アドレスを開始します。</param>
        <param name="endIPAddress">ファイアウォール ルールの IP アドレスを終了します。</param>
        <param name="firewallRuleName">ファイアウォール ルールの名前。</param>
        <summary>
            SQL Server の新しいファイアウォール ルールを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server 更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithoutFirewallRule (string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate WithoutFirewallRule(string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IWithFirewallRule.WithoutFirewallRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFirewallRule (firewallRuleName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFirewallRule : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate" Usage="iWithFirewallRule.WithoutFirewallRule firewallRuleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="firewallRuleName">削除するファイアウォール ルールの名前です。</param>
        <summary>
            SQL Server からファイアウォール規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SQL Server 更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>