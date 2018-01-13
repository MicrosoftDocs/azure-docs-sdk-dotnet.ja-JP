<Type Name="VirtualMachineScaleSetVMProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セットの仮想マシン プロファイルをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetVMProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile (Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor(Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile (osProfile, storageProfile, networkProfile, diagnosticsProfile, extensionProfile, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="extensionProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osProfile">スケール セット内の仮想マシンのオペレーティング システムの設定を指定します。</param>
        <param name="storageProfile">仮想マシンのディスクの記憶域の設定を指定します。</param>
        <param name="networkProfile">スケール セット内の仮想マシンのネットワーク インターフェイスのプロパティを指定します。</param>
        <param name="diagnosticsProfile">ブート診断設定の状態を指定します。 &lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15 です。</param>
        <param name="extensionProfile">仮想マシン スケール セット内にインストールされている拡張機能の設定のコレクションを指定します。</param>
        <param name="licenseType">イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。 この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。
            &lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt;Windows_Server &lt;br&gt;&lt;br&gt;この要素が更新プログラムの要求に含まれている場合、値が初期値に一致する必要があります。 この値を更新することはできません。 &lt;ブラジル&gt;&lt;br&gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt;最小値。api バージョン: 2015-06-15</param>
        <summary>
            VirtualMachineScaleSetVMProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、ブート診断設定の状態を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionProfile As VirtualMachineScaleSetExtensionProfile" />
      <MemberSignature Language="F#" Value="member this.ExtensionProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシン スケール セット内にインストールされている拡張機能の設定のコレクションを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。 この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Client &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Server &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この要素が更新プログラムの要求に含まれている場合、値は、初期値と一致する必要があります。
            この値を更新することはできません。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;最小 api バージョン: 2015-06-15
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As VirtualMachineScaleSetNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、スケール セット内の仮想マシンのネットワーク インターフェイスのプロパティを指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As VirtualMachineScaleSetOSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、スケール セット内の仮想マシンのオペレーティング システムの設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As VirtualMachineScaleSetStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンのディスクの記憶域の設定を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVMProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>