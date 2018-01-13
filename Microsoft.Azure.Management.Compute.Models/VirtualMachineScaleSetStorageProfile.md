<Type Name="VirtualMachineScaleSetStorageProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetStorageProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetStorageProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetStorageProfile = class" />
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
            仮想マシン スケール セットのストレージ プロファイルをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetStorageProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.#ctor" />
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
            VirtualMachineScaleSetStorageProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetStorageProfile (Microsoft.Azure.Management.Compute.Models.ImageReference imageReference = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk osDisk = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; dataDisks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.ImageReference imageReference, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk osDisk, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; dataDisks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ImageReference,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile : Microsoft.Azure.Management.Compute.Models.ImageReference * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile (imageReference, osDisk, dataDisks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageReference" Type="Microsoft.Azure.Management.Compute.Models.ImageReference" />
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="imageReference">使用するイメージに関する情報を指定します。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージに関する情報を指定することができます。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージを使用するが、その他の作成操作で使用されていない場合、この要素が必要です。</param>
        <param name="osDisk">仮想マシン スケール セット内で使用されるオペレーティング システム ディスクに関する情報を指定します。
            &lt;ブラジル&gt;&lt;br&gt;ディスクの詳細については、次を参照してください。[ディスクと Azure の仮想マシンの Vhd について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。</param>
        <param name="dataDisks">データ ディスクを仮想マシン スケール セット内に追加するために使用されるパラメーターを指定します。
            &lt;ブラジル&gt;&lt;br&gt;ディスクの詳細については、次を参照してください。[ディスクと Azure の仮想マシンの Vhd について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。</param>
        <summary>
            VirtualMachineScaleSetStorageProfile クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of VirtualMachineScaleSetDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、データ ディスクを仮想マシン スケール セット内に追加するために使用されるパラメーターを指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;ディスクの詳細については、次を参照してください。[ディスクと Azure の仮想マシンの Vhd について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ImageReference ImageReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ImageReference ImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.ImageReference" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.ImageReference : Microsoft.Azure.Management.Compute.Models.ImageReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.ImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を使用するイメージに関する情報を指定します。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージに関する情報を指定することができます。 プラットフォーム イメージ、marketplace イメージまたは仮想マシンのイメージを使用するが、その他の作成操作で使用されていない場合、この要素が必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As VirtualMachineScaleSetOSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシン スケール セット内で使用されるオペレーティング システム ディスクに関する情報を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;ディスクの詳細については、次を参照してください。[ディスクと Azure の仮想マシンの Vhd について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetStorageProfile.Validate " />
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