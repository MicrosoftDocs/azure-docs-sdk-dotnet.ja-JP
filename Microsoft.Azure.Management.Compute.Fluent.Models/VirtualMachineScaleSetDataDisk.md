<Type Name="VirtualMachineScaleSetDataDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetDataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetDataDisk" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetDataDisk = class" />
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
            仮想マシン スケール セットのデータ ディスクをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetDataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            VirtualMachineScaleSetDataDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetDataDisk (int lun, Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes createOption, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.#ctor(System.Int32,Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, createOption As DiskCreateOptionTypes, Optional name As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional managedDisk As VirtualMachineScaleSetManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk : int * Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk (lun, createOption, name, caching, diskSizeGB, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="lun">論理ユニットの数です。</param>
        <param name="createOption">作成のオプションです。 使用可能な値が含まれます: 'fromImage'、'empty' に 'attach'</param>
        <param name="name">ディスクの名前。</param>
        <param name="caching">キャッシュの型。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</param>
        <param name="diskSizeGB">空のデータ ディスクの初期のディスク サイズ GB と既存の OS とデータ ディスクの新しいサイズ。</param>
        <param name="managedDisk">管理対象ディスクのパラメーターです。</param>
        <summary>
            VirtualMachineScaleSetDataDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Caching" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Fluent.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.CreateOption" />
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
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または空のデータ ディスクの場合は、GB、初期のディスク サイズと既存の OS とデータ ディスクの新しいサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または論理ユニット番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As VirtualMachineScaleSetManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.ManagedDisk" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Name" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetDataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetDataDisk.Validate " />
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
  </Members>
</Type>