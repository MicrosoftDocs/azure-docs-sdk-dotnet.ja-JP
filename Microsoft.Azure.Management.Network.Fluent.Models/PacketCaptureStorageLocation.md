<Type Name="PacketCaptureStorageLocation" FullName="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation">
  <TypeSignature Language="C#" Value="public class PacketCaptureStorageLocation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureStorageLocation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureStorageLocation" />
  <TypeSignature Language="F#" Value="type PacketCaptureStorageLocation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            パケット キャプチャ セッションの記憶域の場所を説明します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureStorageLocation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PacketCaptureStorageLocation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureStorageLocation (string storageId = null, string storagePath = null, string filePath = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageId, string storagePath, string filePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageId As String = null, Optional storagePath As String = null, Optional filePath As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation (storageId, storagePath, filePath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageId" Type="System.String" />
        <Parameter Name="storagePath" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageId">パケットを保存するストレージ アカウントの ID は、セッションをキャプチャします。 ローカル ファイル パスが指定されていないかどうかは必須です。</param>
        <param name="storagePath">パケット キャプチャを保存する記憶域のパスの URI。 必要がある整形式 URI 場所を示すパケット キャプチャを保存します。</param>
        <param name="filePath">ターゲットの VM 上の有効なローカル パス。 キャプチャ ファイルの名前を含める必要があります (* .cap)。 Linux 仮想マシンの先頭には/var/captures します。 かどうかは記憶域を提供されている、それ以外の場合省略可能な必要です。</param>
        <summary>
            PacketCaptureStorageLocation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはターゲットの仮想マシンで有効なローカル パスを設定します。 キャプチャ ファイルの名前を含める必要があります (* .cap)。 Linux 仮想マシンの先頭には/var/captures します。 かどうかは記憶域を提供されている、それ以外の場合省略可能な必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageId">
      <MemberSignature Language="C#" Value="public string StorageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StorageId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageId As String" />
      <MemberSignature Language="F#" Value="member this.StorageId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StorageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ セッションを保存するストレージ アカウントの ID を設定します。 ローカル ファイル パスが指定されていないかどうかは必須です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoragePath">
      <MemberSignature Language="C#" Value="public string StoragePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoragePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StoragePath" />
      <MemberSignature Language="VB.NET" Value="Public Property StoragePath As String" />
      <MemberSignature Language="F#" Value="member this.StoragePath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.PacketCaptureStorageLocation.StoragePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storagePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャを保存する記憶域のパスの URI を設定します。 必要がある整形式 URI 場所を示すパケット キャプチャを保存します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>