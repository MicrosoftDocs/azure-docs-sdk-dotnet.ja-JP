<Type Name="VirtualMachineScaleSetUpdateOSDisk" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdateOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdateOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdateOSDisk" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdateOSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セットのオペレーティング システム ディスクの更新オブジェクトについて説明します。 VMSS OS ディスクの更新のために使用する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetUpdateOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateOSDisk (Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image = null, System.Collections.Generic.IList&lt;string&gt; vhdContainers = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image, class System.Collections.Generic.IList`1&lt;string&gt; vhdContainers, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional caching As Nullable(Of CachingTypes) = null, Optional image As VirtualHardDisk = null, Optional vhdContainers As IList(Of String) = null, Optional managedDisk As VirtualMachineScaleSetManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk (caching, image, vhdContainers, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="vhdContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="caching">キャッシュの型。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</param>
        <param name="image">ソース ユーザー イメージ VirtualHardDisk です。 仮想マシンへの接続に使用する前にこの VirtualHardDisk がコピーされます。 SourceImage を指定すると、送信先 VirtualHardDisk が存在しない必要があります。</param>
        <param name="vhdContainers">仮想ハード ディスク コンテナーの一覧の uri。</param>
        <param name="managedDisk">管理対象ディスクのパラメーターです。</param>
        <summary>
            VirtualMachineScaleSetUpdateOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキャッシュの種類を設定します。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはソース ユーザー イメージ VirtualHardDisk を設定します。 仮想マシンへの接続に使用する前にこの VirtualHardDisk がコピーされます。 SourceImage を指定すると、送信先 VirtualHardDisk が存在しない必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As VirtualMachineScaleSetManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理対象ディスク パラメーターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VhdContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateOSDisk.VhdContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhdContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            仮想ハード ディスク コンテナーの一覧を取得または uri。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>