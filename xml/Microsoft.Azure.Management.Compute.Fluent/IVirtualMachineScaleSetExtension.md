<Type Name="IVirtualMachineScaleSetExtension" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetExtension : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetExtension implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetExtension&#xA;Implements IChildResource(Of IVirtualMachineScaleSet), IHasInner(Of VirtualMachineScaleSetExtension), IHasParent(Of IVirtualMachineScaleSet)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetExtension = interface&#xA;    interface IHasInner&lt;VirtualMachineScaleSetExtension&gt;&#xA;    interface IChildResource&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IVirtualMachineScaleSet&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetExtension&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="228b5-101">スケールの仮想マシンに関連付けられている拡張機能の変更できないクライアント側表現を設定します。</span><span class="sxs-lookup"><span data-stu-id="228b5-101">An immutable client-side representation of an extension associated with virtual machines in a scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoUpgradeMinorVersionEnabled">
      <MemberSignature Language="C#" Value="public bool AutoUpgradeMinorVersionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoUpgradeMinorVersionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.AutoUpgradeMinorVersionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoUpgradeMinorVersionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoUpgradeMinorVersionEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.AutoUpgradeMinorVersionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-102">この拡張機能に基づいている拡張機能のイメージの場合は、新しいマイナー バージョンを公開するときに自動的にアップグレードするこの拡張機能が構成されている場合は true を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-102">Gets true if this extension is configured to upgrade automatically when a new minor version of the extension image that this extension based on is published.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-103">この仮想マシンのスケールのプロビジョニングの状態のセットの拡張機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-103">Gets the provisioning state of this virtual machine scale set extension.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,object&gt; PublicSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, object&gt; PublicSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublicSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicSettings As IReadOnlyDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.PublicSettings : System.Collections.Generic.IReadOnlyDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublicSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-104">取得パブリック仮想マシンのスケールの設定は、キー値のペアとしての拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="228b5-104">Gets the public settings of the virtual machine scale set extension as key value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicSettingsAsJsonString">
      <MemberSignature Language="C#" Value="public string PublicSettingsAsJsonString { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicSettingsAsJsonString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublicSettingsAsJsonString" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicSettingsAsJsonString As String" />
      <MemberSignature Language="F#" Value="member this.PublicSettingsAsJsonString : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublicSettingsAsJsonString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-105">JSON 文字列として仮想マシンの拡張機能のパブリック、設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-105">Gets the public settings of the virtual machine extension as a JSON string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherName">
      <MemberSignature Language="C#" Value="public string PublisherName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublisherName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublisherName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublisherName As String" />
      <MemberSignature Language="F#" Value="member this.PublisherName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.PublisherName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-106">この拡張機能が作成された仮想マシン スケール セット拡張イメージのパブリッシャーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-106">Gets the publisher name of the virtual machine scale set extension image this extension is created from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeName">
      <MemberSignature Language="C#" Value="public string TypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.TypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeName As String" />
      <MemberSignature Language="F#" Value="member this.TypeName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.TypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-107">この拡張機能が作成された仮想マシン スケール セット拡張イメージの型名を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-107">Gets the type name of the virtual machine scale set extension image this extension is created from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionName">
      <MemberSignature Language="C#" Value="public string VersionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.VersionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionName As String" />
      <MemberSignature Language="F#" Value="member this.VersionName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension.VersionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="228b5-108">この拡張機能が作成された仮想マシン スケール セット拡張イメージのバージョン名を取得します。</span><span class="sxs-lookup"><span data-stu-id="228b5-108">Gets the version name of the virtual machine scale set extension image this extension is created from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>