<Type Name="DataDisk" FullName="Microsoft.Azure.Management.Batch.Models.DataDisk">
  <TypeSignature Language="C#" Value="public class DataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.DataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class DataDisk" />
  <TypeSignature Language="F#" Value="type DataDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プール内のコンピューティング ノードに関連付けられているデータ ディスクで使用されるデータ ディスクの設定。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            DataDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataDisk (int lun, int diskSizeGB, Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, int32 diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.#ctor(System.Int32,System.Int32,System.Nullable{Microsoft.Azure.Management.Batch.Models.CachingType},System.Nullable{Microsoft.Azure.Management.Batch.Models.StorageAccountType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, diskSizeGB As Integer, Optional caching As Nullable(Of CachingType) = null, Optional storageAccountType As Nullable(Of StorageAccountType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.DataDisk : int * int * Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; -&gt; Microsoft.Azure.Management.Batch.Models.DataDisk" Usage="new Microsoft.Azure.Management.Batch.Models.DataDisk (lun, diskSizeGB, caching, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="diskSizeGB" Type="System.Int32" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt;" />
      </Parameters>
      <Docs>
        <param name="lun">論理ユニットの数です。</param>
        <param name="diskSizeGB">最初のディスク サイズ GB 新しいデータ ディスクを作成するときにします。</param>
        <param name="caching">データ ディスクに対して有効にするキャッシュの型。</param>
        <param name="storageAccountType">データ ディスクとして使用するストレージ アカウントの種類。</param>
        <summary>
            DataDisk クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得またはデータ ディスクに対して有効にするキャッシュの種類を設定します。
             </summary>
        <value>To be added.</value>
        <remarks>
             値は次のとおりです。
            
             なし: ディスクのキャッシュ モードは無効です。
             読み取り専用のディスクのキャッシュ モードは読み取り専用です。
             readWrite のディスクのキャッシュ モードは読み書きします。
            
             キャッシュの既定値は none です。 キャッシュのオプションに関する情報を参照してください: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/です。
             使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public int DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Integer" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または新しいデータ ディスクを作成するときに、最初のディスク サイズを GB に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <remarks>
            Lun を使用して、各データ ディスクを一意に識別します。 複数のディスクをアタッチするには、それぞれが個別の lun を持ちます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountType)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.StorageAccountType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得またはデータ ディスクを使用するストレージ アカウントの種類を設定します。
             </summary>
        <value>To be added.</value>
        <remarks>
             省略した場合、既定値は"Standard_LRS"にします。 値は次のとおりです。
            
             Standard_LRS - データ ディスクは、標準のローカル冗長ストレージを使用してください。
             Premium_LRS - データ ディスクは、premium ローカル冗長ストレージを使用する必要があります。 使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataDisk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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