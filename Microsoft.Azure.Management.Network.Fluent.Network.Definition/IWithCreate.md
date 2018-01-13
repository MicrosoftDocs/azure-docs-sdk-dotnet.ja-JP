<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of INetwork), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;INetwork&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            含むすべての最低限必要な入力を作成するリソースの仮想ネットワーク定義のステージ (WithCreate.create()) を使用してサブネットを追加することを除き、指定する省略可能なその他の設定も可能ですが。
            サブネットに追加できるだけ右後、アドレス空間が明示的に指定された (WithCreate.withAddressSpace(String)) 参照します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithAddressSpace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressSpace (cidr As String) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithAddressSpace : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithCreate.WithAddressSpace cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">アドレス空間の CIDR 表記します。</param>
        <summary>
            仮想ネットワークにアドレス空間が明示的に追加します。
            アドレス空間を明示的に指定していない場合、既定ではアドレス空間 CIDR「10.0.0.0/16」は、仮想ネットワークに割り当てられます。
            このメソッドの効果は加法、つまりそれを使用するたび、新しいアドレス空間がネットワークに追加します。
            このメソッドは、競合をチェックしませんまたはその他のアドレス空間と重複しています。 競合がある場合は、ネットワークの作成時にクラウド例外がスローされる可能性がします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" Usage="iWithCreate.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">DNS サーバーの IP アドレス。</param>
        <summary>
            仮想ネットワークに関連付ける既存の DNS サーバーの IP アドレスを指定します。
            このメソッドの効果は加法、つまりそれを使用するたび、新しい dns サーバーがネットワークに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>