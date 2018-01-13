<Type Name="IWithTags&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithTags&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTags&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTags`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithTags`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTags(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTags&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るに親の更新の段階です。</typeparam>
    <summary>
            タグを指定できるように仮想マシン拡張機能の定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithTags`1.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTags.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">タグのキー。</param>
        <param name="value">タグの値です。</param>
        <summary>
            リソースにタグを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTags.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">リソースに関連付けるタグを付けます。</param>
        <summary>
            リソースのタグを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>