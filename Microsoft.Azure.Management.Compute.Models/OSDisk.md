<Type Name="OSDisk" FullName="Microsoft.Azure.Management.Compute.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
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
            仮想マシンによって使用されるオペレーティング システム ディスクに関する情報を指定します。 &lt;ブラジル&gt;&lt;br&gt;ディスクの詳細については、次を参照してください。[ディスクと Azure の仮想マシンの Vhd について](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.#ctor" />
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
            OSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings encryptionSettings = null, string name = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk vhd = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings encryptionSettings, string name, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk vhd, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes,System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings,System.String,Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional encryptionSettings As DiskEncryptionSettings = null, Optional name As String = null, Optional vhd As VirtualHardDisk = null, Optional image As VirtualHardDisk = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional managedDisk As ManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.OSDisk : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings * string * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Models.OSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.OSDisk (createOption, osType, encryptionSettings, name, vhd, image, caching, diskSizeGB, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="vhd" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="createOption">仮想マシンを作成する方法を指定します。&lt;br&gt;&lt;br&gt;指定できる値は:&lt;br&gt;&lt;br&gt; **アタッチ**\u2013 を使用しているときにこの値が使用される、専用のディスクを仮想マシンを作成します。&lt;br&gt;&lt;br&gt; **FromImage** \u2013 仮想マシンを作成するイメージを使用しているときに、この値を使用します。 プラットフォーム イメージを使用している場合は、上記で説明した imageReference 要素を使用します。 Marketplace イメージを使用している場合は、前に説明した計画の要素を使用します。 使用可能な値が含まれます: 'FromImage'、'Empty'、'接続'</param>
        <param name="osType">このプロパティでは、ユーザー イメージまたは特殊な VHD から VM を作成する場合に、ディスクに含まれている OS の種類を指定することができます。 &lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt; &lt;br&gt; **Linux**です。 使用可能な値が含まれます 'Windows'、'Linux'。</param>
        <param name="encryptionSettings">OS ディスクの暗号化の設定を指定します。 &lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15</param>
        <param name="name">ディスクの名前。</param>
        <param name="vhd">バーチャル ハード_ディスク。</param>
        <param name="image">送信元のユーザーは、バーチャル ハード_ディスクをイメージします。 仮想マシンにアタッチされる前に、バーチャル ハード_ディスクがコピーされます。 SourceImage を指定すると、移行先の仮想ハード ドライブが存在しない必要があります。</param>
        <param name="caching">キャッシュの要件を指定します。
            &lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt; &lt;ブラジル&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt; &lt;br&gt;既定:**標準的な記憶域については None です。Premium storage の ReadOnly**です。 使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</param>
        <param name="diskSizeGB">空のデータ ディスクのサイズをギガバイト単位で指定します。 この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。 &lt;ブラジル&gt;&lt;br&gt;この値は、1,023 GB より大きくすることはできません</param>
        <param name="managedDisk">管理対象ディスクのパラメーターです。</param>
        <summary>
            OSDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Caching" />
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
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、仮想マシンを作成する方法を指定します。&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は:&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**アタッチ**\u2013 仮想マシンを作成する専用のディスクを使用しているときに、この値を使用します&amp;。lt; br&amp;gt;&amp;lt; br&amp;gt;**FromImage** \u2013 仮想マシンを作成するイメージを使用しているときに、この値を使用します。 プラットフォーム イメージを使用している場合は、上記で説明した imageReference 要素を使用します。 Marketplace イメージを使用している場合は、前に説明した計画の要素を使用します。 使用可能な値が含まれます: 'FromImage'、'Empty'、'接続'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.DiskSizeGB" />
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
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As DiskEncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskEncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、OS ディスクの暗号化の設定を指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            取得または元のユーザー イメージ仮想ハード_ディスクを設定します。 仮想マシンにアタッチされる前に、バーチャル ハード_ディスクがコピーされます。 SourceImage を指定すると、移行先の仮想ハード ドライブが存在しない必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As ManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.ManagedDisk" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ManagedDiskParameters</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.OsType" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、このプロパティを使用すると、ユーザー イメージまたは特殊な VHD から VM を作成する場合に、ディスクに含まれている OS の種類を指定できます。 &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Linux**です。 使用可能な値が含まれます 'Windows'、'Linux'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.OSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="oSDisk.Validate " />
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
    <Member MemberName="Vhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Vhd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Vhd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.OSDisk.Vhd" />
      <MemberSignature Language="VB.NET" Value="Public Property Vhd As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Vhd : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.OSDisk.Vhd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバーチャル ハード_ディスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>