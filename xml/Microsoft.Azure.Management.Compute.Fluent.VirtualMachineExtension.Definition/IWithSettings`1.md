<Type Name="IWithSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSettings&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSettings`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSettings(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSettings&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="5740e-101">この定義をアタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="5740e-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5740e-102">パブリックおよびプライベートの設定を指定できるように仮想マシン拡張機能の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="5740e-102">The stage of the virtual machine extension definition allowing to specify the public and private settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithProtectedSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithProtectedSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithProtectedSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings`1.WithProtectedSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSetting (key As String, value As Object) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSettings.WithProtectedSetting (key, value)" />
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
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5740e-103">プライベート設定のエントリのキー。</span><span class="sxs-lookup"><span data-stu-id="5740e-103">The key of a private settings entry.</span></span></param>
        <param name="value"><span data-ttu-id="5740e-104">プライベート設定のエントリの値。</span><span class="sxs-lookup"><span data-stu-id="5740e-104">The value of the private settings entry.</span></span></param>
        <summary>
            <span data-ttu-id="5740e-105">プライベート設定のエントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="5740e-105">Specifies a private settings entry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5740e-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5740e-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithProtectedSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithProtectedSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithProtectedSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings`1.WithProtectedSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSettings (settings As IDictionary(Of String, Object)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSettings.WithProtectedSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="5740e-107">プライベート設定します。</span><span class="sxs-lookup"><span data-stu-id="5740e-107">The private settings.</span></span></param>
        <summary>
            <span data-ttu-id="5740e-108">プライベート設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="5740e-108">Specifies private settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5740e-109">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5740e-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithPublicSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithPublicSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings`1.WithPublicSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSetting (key As String, value As Object) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSettings.WithPublicSetting (key, value)" />
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
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="5740e-110">公開設定のエントリのキー。</span><span class="sxs-lookup"><span data-stu-id="5740e-110">The key of a public settings entry.</span></span></param>
        <param name="value"><span data-ttu-id="5740e-111">公開設定のエントリの値。</span><span class="sxs-lookup"><span data-stu-id="5740e-111">The value of the public settings entry.</span></span></param>
        <summary>
            <span data-ttu-id="5740e-112">公開設定のエントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="5740e-112">Specifies a public settings entry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5740e-113">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5740e-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithPublicSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithPublicSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithSettings`1.WithPublicSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSettings (settings As IDictionary(Of String, Object)) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSettings.WithPublicSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="5740e-114">公開設定。</span><span class="sxs-lookup"><span data-stu-id="5740e-114">The public settings.</span></span></param>
        <summary>
            <span data-ttu-id="5740e-115">公開設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="5740e-115">Specifies public settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5740e-116">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5740e-116">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>