<Type Name="VirtualMachineScaleSetOSDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetOSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            仮想マシン スケール セットのオペレーティング システム ディスクをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk (Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image = null, System.Collections.Generic.IList&lt;string&gt; vhdContainers = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk image, class System.Collections.Generic.IList`1&lt;string&gt; vhdContainers, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional name As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional image As VirtualHardDisk = null, Optional vhdContainers As IList(Of String) = null, Optional managedDisk As VirtualMachineScaleSetManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk (createOption, name, caching, osType, image, vhdContainers, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk" />
        <Parameter Name="vhdContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="createOption">作成のオプションです。 使用可能な値が含まれます: 'fromImage'、'empty' に 'attach'</param>
        <param name="name">ディスクの名前。</param>
        <param name="caching">キャッシュの型。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</param>
        <param name="osType">オペレーティング システムの種類。 使用可能な値が含まれます 'Windows'、'Linux'。</param>
        <param name="image">ソース ユーザー イメージ VirtualHardDisk です。 仮想マシンへの接続に使用する前にこの VirtualHardDisk がコピーされます。 SourceImage を指定すると、送信先 VirtualHardDisk が存在しない必要があります。</param>
        <param name="vhdContainers">仮想ハード ディスク コンテナーの一覧の uri。</param>
        <param name="managedDisk">管理対象ディスクのパラメーターです。</param>
        <summary>
            VirtualMachineScaleSetOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキャッシュの種類を設定します。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または作成する オプションを設定します。 使用可能な値が含まれます: 'fromImage'、'empty' に 'attach'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualHardDisk</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As VirtualMachineScaleSetManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または管理対象ディスク パラメーターを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはディスクの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはオペレーティング システムの種類を設定します。 使用可能な値が含まれます 'Windows'、'Linux'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetOSDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VhdContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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