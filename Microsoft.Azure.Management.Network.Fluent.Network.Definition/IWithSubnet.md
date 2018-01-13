<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サブネットを追加できるように、仮想ネットワーク定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt; DefineSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt; DefineSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.DefineSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSubnet (name As String) As IBlank(Of IWithCreateAndSubnet)" />
      <MemberSignature Language="F#" Value="abstract member DefineSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt;" Usage="iWithSubnet.DefineSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">サブネットの名前。</param>
        <summary>
            仮想ネットワークに追加する新しいサブネットの定義を開始します。
            定義は、Subnet.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しいサブネットの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnet (string name, string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnet(string name, string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.WithSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String, cidr As String) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithSubnet.WithSubnet (name, cidr)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">サブネットに割り当てる名前。</param>
        <param name="cidr">CIDR 表記を使用して、ネットワークのアドレス空間内のサブネットのアドレス空間です。</param>
        <summary>
            仮想ネットワークにサブネットが明示的に追加します。
            既定のサブネットが"subnet1"と呼ばれるサブネットは、明示的に指定しない場合、全体をカバーする最初のアドレス空間が作成されます。
            このメソッドの効果は加法、つまりそれを使用するたび、新しいサブネットがネットワークに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnets (System.Collections.Generic.IDictionary&lt;string,string&gt; nameCidrPairs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithSubnets(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; nameCidrPairs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithSubnet.WithSubnets(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnets (nameCidrPairs As IDictionary(Of String, String)) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithSubnets : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithSubnet.WithSubnets nameCidrPairs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameCidrPairs" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nameCidrPairs">マップの CIDR アドレスがサブネットを定義するには、各サブネットの名前によってインデックス設定。</param>
        <summary>
            明示的に指定されたマップに基づき、仮想ネットワークのサブネットを定義します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>