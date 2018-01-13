<Type Name="ImageOSDisk" FullName="Microsoft.Azure.Management.Compute.Models.ImageOSDisk">
  <TypeSignature Language="C#" Value="public class ImageOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageOSDisk" />
  <TypeSignature Language="F#" Value="type ImageOSDisk = class" />
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
            オペレーティング システム ディスクをについて説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.#ctor" />
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
            ImageOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk (Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes osState, Microsoft.Azure.Management.Compute.Models.SubResource snapshot = null, Microsoft.Azure.Management.Compute.Models.SubResource managedDisk = null, string blobUri = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes osState, class Microsoft.Azure.Management.Compute.Models.SubResource snapshot, class Microsoft.Azure.Management.Compute.Models.SubResource managedDisk, string blobUri, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes,Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes,Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osType As OperatingSystemTypes, osState As OperatingSystemStateTypes, Optional snapshot As SubResource = null, Optional managedDisk As SubResource = null, Optional blobUri As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageOSDisk : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes * Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.SubResource * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ImageOSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.ImageOSDisk (osType, osState, snapshot, managedDisk, blobUri, caching, diskSizeGB, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="osType">このプロパティでは、カスタム イメージから VM を作成する場合に、ディスクに含まれている OS の種類を指定することができます。 &lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt; &lt;br&gt; **Linux**です。
            使用可能な値が含まれます 'Windows'、'Linux'。</param>
        <param name="osState">OS の状態。 使用可能な値が含まれます: '汎用'、'特殊化'</param>
        <param name="snapshot">スナップショット。</param>
        <param name="managedDisk">ManagedDisk です。</param>
        <param name="blobUri">バーチャル ハード_ディスク。</param>
        <param name="caching">キャッシュの要件を指定します。
            &lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt; &lt;ブラジル&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt; &lt;br&gt;既定:**標準的な記憶域については None です。Premium storage の ReadOnly**です。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</param>
        <param name="diskSizeGB">空のデータ ディスクのサイズをギガバイト単位で指定します。 この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。 &lt;ブラジル&gt;&lt;br&gt;この値は、1,023 GB より大きくすることはできません</param>
        <param name="storageAccountType">管理対象ディスクのストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。 使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</param>
        <summary>
            ImageOSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.BlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバーチャル ハード_ディスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            取得または設定は、キャッシュの要件を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**None** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadOnly** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadWrite** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;既定値:**標準的な記憶域については None です。Premium storage の ReadOnly**です。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            取得または設定は、空のデータ ディスクのサイズをギガバイト単位で指定します。
            この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この値は、1,023 GB より大きくすることはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As SubResource" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、managedDisk を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes OsState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes OsState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsState" />
      <MemberSignature Language="VB.NET" Value="Public Property OsState As OperatingSystemStateTypes" />
      <MemberSignature Language="F#" Value="member this.OsState : Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OS の状態を設定します。 使用可能な値が含まれます: '汎用'、'特殊化'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OsType : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、このプロパティを使用すると、カスタム イメージから VM を作成する場合に、ディスクに含まれている OS の種類を指定できます。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Linux**です。 使用可能な値が含まれます 'Windows'、'Linux'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource Snapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource Snapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property Snapshot As SubResource" />
      <MemberSignature Language="F#" Value="member this.Snapshot : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Snapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="snapshot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスナップショットを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、管理対象ディスクのストレージ アカウントの種類を指定します。 指定できる値は: Standard_LRS またはが premium_lrs の場合。 使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageOSDisk.Validate " />
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