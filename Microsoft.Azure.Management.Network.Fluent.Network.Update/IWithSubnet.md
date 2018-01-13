<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            仮想ネットワークのステージでは、追加またはサブネットを削除する許可を更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.DefineSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSubnet (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;" Usage="iWithSubnet.DefineSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しいサブネットの名前。</param>
        <summary>
            この仮想ネットワークに追加する新しいサブネットの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>新しいサブネットの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.UpdateSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithSubnet.UpdateSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">既存のサブネットの名前。</param>
        <summary>
            このネットワークの既存のサブネットの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブネットの更新プログラムの説明の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithoutSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithoutSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除するサブネットの名前です。</param>
        <summary>
            仮想ネットワークのサブネットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想ネットワークの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet (string name, string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet(string name, string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String, cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnet (name, cidr)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
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
            このメソッドの効果は加法、つまりそれを使用するたび、新しいサブネットがネットワークに追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想ネットワークの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets (System.Collections.Generic.IDictionary&lt;string,string&gt; nameCidrPairs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; nameCidrPairs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnets(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnets (nameCidrPairs As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnets : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnets nameCidrPairs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameCidrPairs" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nameCidrPairs">マップの CIDR アドレスがサブネットを追加するには、各サブネットの名前によってインデックス設定。</param>
        <summary>
            明示的に指定されたマップに基づき、仮想ネットワークのすべてのサブネットを定義します。
            これには、既存のサブネットが置き換えられます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>仮想ネットワークの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>