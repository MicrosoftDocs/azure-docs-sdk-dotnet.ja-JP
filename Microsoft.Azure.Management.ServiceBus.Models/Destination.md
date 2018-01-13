<Type Name="Destination" FullName="Microsoft.Azure.Management.ServiceBus.Models.Destination">
  <TypeSignature Language="C#" Value="public class Destination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Destination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Destination" />
  <TypeSignature Language="VB.NET" Value="Public Class Destination" />
  <TypeSignature Language="F#" Value="type Destination = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            キャプチャ記憶域の詳細がキャプチャの説明
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Destination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            変換先のクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination (string name = null, string storageAccountResourceId = null, string blobContainer = null, string archiveNameFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string storageAccountResourceId, string blobContainer, string archiveNameFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Destination.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional storageAccountResourceId As String = null, Optional blobContainer As String = null, Optional archiveNameFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Destination : string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.Destination" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Destination (name, storageAccountResourceId, blobContainer, archiveNameFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageAccountResourceId" Type="System.String" />
        <Parameter Name="blobContainer" Type="System.String" />
        <Parameter Name="archiveNameFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">キャプチャ対象の名前</param>
        <param name="storageAccountResourceId">Blob の作成に使用するストレージ アカウントのリソース id</param>
        <param name="blobContainer">Blob コンテナー名</param>
        <param name="archiveNameFormat">Blob の名前付け規則、アーカイブの例: {Namespace}/{EventHub}/{PartitionId}/{year}/{月}/{日}/{時間}/{分}/{秒}。
            ここで、すべてのパラメーター (Namespace、EventHub.. その他) は順序に関係なく、必須</param>
        <summary>
            変換先のクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ArchiveNameFormat">
      <MemberSignature Language="C#" Value="public string ArchiveNameFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ArchiveNameFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.ArchiveNameFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property ArchiveNameFormat As String" />
      <MemberSignature Language="F#" Value="member this.ArchiveNameFormat : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.ArchiveNameFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.archiveNameFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定 blob の名前付け規則、アーカイブの例: {Namespace}/{EventHub}/{PartitionId}/{year}/{月}/{日}/{時間}/{分}/{秒}。
            ここで、すべてのパラメーター (Namespace、EventHub.. その他) は順序に関係なく、必須
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobContainer">
      <MemberSignature Language="C#" Value="public string BlobContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.BlobContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobContainer As String" />
      <MemberSignature Language="F#" Value="member this.BlobContainer : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.BlobContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または blob コンテナー名を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得または設定のキャプチャ対象の名前
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountResourceId">
      <MemberSignature Language="C#" Value="public string StorageAccountResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.StorageAccountResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountResourceId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountResourceId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.StorageAccountResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、blob の作成に使用するストレージ アカウントのリソース id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>