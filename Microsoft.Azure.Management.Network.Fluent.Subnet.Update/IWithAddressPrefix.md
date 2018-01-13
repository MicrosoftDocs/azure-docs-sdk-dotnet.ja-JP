<Type Name="IWithAddressPrefix" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix">
  <TypeSignature Language="C#" Value="public interface IWithAddressPrefix" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddressPrefix" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddressPrefix" />
  <TypeSignature Language="F#" Value="type IWithAddressPrefix = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サブネットのアドレス空間を変更する許可するサブネットの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithAddressPrefix.WithAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressPrefix (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithAddressPrefix.WithAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">CIDR 表記を使用して IP アドレス空間のプレフィックス。</param>
        <summary>
            ネットワークのアドレス空間内のサブネットの IP アドレス空間を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>