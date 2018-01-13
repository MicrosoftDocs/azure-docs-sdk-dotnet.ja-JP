<Type Name="IWithSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings">
  <TypeSignature Language="C#" Value="public interface IWithSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSettings" />
  <TypeSignature Language="F#" Value="type IWithSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="55a5e-101">仮想マシンのスケールのステージでは、拡張機能を追加またはパブリックおよびプライベートの設定を更新する更新プログラムを許可するを設定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-101">The stage of a virtual machine scale set extension update allowing to add or update public and private settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithProtectedSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithProtectedSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithProtectedSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings.WithProtectedSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSetting (key As String, value As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithSettings.WithProtectedSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="55a5e-102">プライベート設定のエントリのキー。</span><span class="sxs-lookup"><span data-stu-id="55a5e-102">The key of a private settings entry.</span></span></param>
        <param name="value"><span data-ttu-id="55a5e-103">プライベート設定のエントリの値。</span><span class="sxs-lookup"><span data-stu-id="55a5e-103">The value of the private settings entry.</span></span></param>
        <summary>
            <span data-ttu-id="55a5e-104">プライベート設定のエントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-104">Specifies a private settings entry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="55a5e-105">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="55a5e-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithProtectedSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithProtectedSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithProtectedSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings.WithProtectedSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtectedSettings (settings As IDictionary(Of String, Object)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProtectedSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithSettings.WithProtectedSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="55a5e-106">プライベート設定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-106">The private settings.</span></span></param>
        <summary>
            <span data-ttu-id="55a5e-107">プライベート設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-107">Specifies private settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="55a5e-108">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="55a5e-108">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSetting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithPublicSetting (string key, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithPublicSetting(string key, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings.WithPublicSetting(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSetting (key As String, value As Object) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSetting : string * obj -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithSettings.WithPublicSetting (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="55a5e-109">公開設定のエントリのキー。</span><span class="sxs-lookup"><span data-stu-id="55a5e-109">The key of a public settings entry.</span></span></param>
        <param name="value"><span data-ttu-id="55a5e-110">公開設定のエントリの値。</span><span class="sxs-lookup"><span data-stu-id="55a5e-110">The value of the public settings entry.</span></span></param>
        <summary>
            <span data-ttu-id="55a5e-111">公開設定のエントリを指定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-111">Specifies a public settings entry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="55a5e-112">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="55a5e-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithPublicSettings (System.Collections.Generic.IDictionary&lt;string,object&gt; settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate WithPublicSettings(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IWithSettings.WithPublicSettings(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicSettings (settings As IDictionary(Of String, Object)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicSettings : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate" Usage="iWithSettings.WithPublicSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="55a5e-113">公開設定。</span><span class="sxs-lookup"><span data-stu-id="55a5e-113">The public settings.</span></span></param>
        <summary>
            <span data-ttu-id="55a5e-114">公開設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="55a5e-114">Specifies public settings.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="55a5e-115">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="55a5e-115">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>