<Type Name="IWithSourcePort" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort">
  <TypeSignature Language="C#" Value="public interface IWithSourcePort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourcePort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourcePort" />
  <TypeSignature Language="F#" Value="type IWithSourcePort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            指定するソース ポートを許可するネットワーク規則の説明の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromAnyPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromAnyPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromAnyPort" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAnyPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromAnyPort : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromAnyPort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このルールは、任意のポートを適用するは、します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPort (int port);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPort(int32 port) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPort (port As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromPort port" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="port">発信元ポート番号。</param>
        <summary>
            この規則を適用する発信元ポートを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="FromPortRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPortRange (int from, int to);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate FromPortRange(int32 from, int32 to) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithSourcePort.FromPortRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPortRange (from As Integer, to As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromPortRange : int * int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithSourcePort.FromPortRange (from, to)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.Int32" />
        <Parameter Name="to" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="from">開始ポート番号。</param>
        <param name="to">終了ポート番号。</param>
        <summary>
            この規則を適用するソースのポート範囲を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>