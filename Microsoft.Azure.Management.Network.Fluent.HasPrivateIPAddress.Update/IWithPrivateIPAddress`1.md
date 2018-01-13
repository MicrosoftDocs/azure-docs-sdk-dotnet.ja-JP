<Type Name="IWithPrivateIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIPAddress&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIPAddress`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIPAddress(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithPrivateIPAddress&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">更新プログラムの次のステージ。</typeparam>
    <summary>
            プライベート IP アドレスの変更を許可する更新プログラムの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1.WithPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressDynamic () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressDynamic : unit -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            動的なプライベート IP アドレスの割り当て、関連付けられているサブネット内で有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public ReturnT WithPrivateIPAddressStatic (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithPrivateIPAddressStatic(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1.WithPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateIPAddressStatic (ipAddress As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPAddressStatic : string -&gt; 'ReturnT" Usage="iWithPrivateIPAddress.WithPrivateIPAddressStatic ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">関連付けられているプライベート IP の範囲内の静的 IP アドレス。</param>
        <summary>
            関連付けられているサブネット内にある指定の static のプライベート IP アドレスを割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>