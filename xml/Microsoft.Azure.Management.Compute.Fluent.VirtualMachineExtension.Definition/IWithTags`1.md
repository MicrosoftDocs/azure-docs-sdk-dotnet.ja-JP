<Type Name="IWithTags&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithTags&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTags&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTags`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithTags`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="9272f-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="9272f-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9272f-102">タグを指定できるように仮想マシン拡張機能の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="9272f-102">The stage of the virtual machine extension definition allowing to specify the tags.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithTags`1.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTags.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="9272f-103">タグのキー。</span><span class="sxs-lookup"><span data-stu-id="9272f-103">The key for the tag.</span></span></param>
        <param name="value"><span data-ttu-id="9272f-104">タグの値です。</span><span class="sxs-lookup"><span data-stu-id="9272f-104">The value for the tag.</span></span></param>
        <summary>
            <span data-ttu-id="9272f-105">仮想マシンの拡張機能にタグを追加します。</span><span class="sxs-lookup"><span data-stu-id="9272f-105">Adds a tag to the virtual machine extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9272f-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9272f-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithTags`1.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTags.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="9272f-107">関連付けるタグ。</span><span class="sxs-lookup"><span data-stu-id="9272f-107">The tags to associate.</span></span></param>
        <summary>
            <span data-ttu-id="9272f-108">仮想マシンの拡張機能用のタグを指定します。</span><span class="sxs-lookup"><span data-stu-id="9272f-108">Specifies tags for the virtual machine extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9272f-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9272f-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>