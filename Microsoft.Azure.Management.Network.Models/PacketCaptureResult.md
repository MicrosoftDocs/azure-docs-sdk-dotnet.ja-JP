<Type Name="PacketCaptureResult" FullName="Microsoft.Azure.Management.Network.Models.PacketCaptureResult">
  <TypeSignature Language="C#" Value="public class PacketCaptureResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PacketCaptureResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PacketCaptureResult" />
  <TypeSignature Language="VB.NET" Value="Public Class PacketCaptureResult" />
  <TypeSignature Language="F#" Value="type PacketCaptureResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            パケット キャプチャ セッションに関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PacketCaptureResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PacketCaptureResult (string target, Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, string name = null, string id = null, string etag = null, Nullable&lt;int&gt; bytesToCapturePerPacket = null, Nullable&lt;int&gt; totalBytesPerSession = null, Nullable&lt;int&gt; timeLimitInSeconds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string target, class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation storageLocation, string name, string id, string etag, valuetype System.Nullable`1&lt;int32&gt; bytesToCapturePerPacket, valuetype System.Nullable`1&lt;int32&gt; totalBytesPerSession, valuetype System.Nullable`1&lt;int32&gt; timeLimitInSeconds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; filters, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.#ctor(System.String,Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.PacketCaptureFilter},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (target As String, storageLocation As PacketCaptureStorageLocation, Optional name As String = null, Optional id As String = null, Optional etag As String = null, Optional bytesToCapturePerPacket As Nullable(Of Integer) = null, Optional totalBytesPerSession As Nullable(Of Integer) = null, Optional timeLimitInSeconds As Nullable(Of Integer) = null, Optional filters As IList(Of PacketCaptureFilter) = null, Optional provisioningState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PacketCaptureResult : string * Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.PacketCaptureResult" Usage="new Microsoft.Azure.Management.Network.Models.PacketCaptureResult (target, storageLocation, name, id, etag, bytesToCapturePerPacket, totalBytesPerSession, timeLimitInSeconds, filters, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="storageLocation" Type="Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="bytesToCapturePerPacket" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalBytesPerSession" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeLimitInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="filters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="target">対象のリソースのみの VM の ID は現在サポートされています。</param>
        <param name="storageLocation">To be added.</param>
        <param name="name">パケット キャプチャ セッションの名前です。</param>
        <param name="id">パケット キャプチャ操作の ID です。</param>
        <param name="etag">To be added.</param>
        <param name="bytesToCapturePerPacket">数パケットごとに取得 (バイト単位) の残りのバイトが切り捨てられます。</param>
        <param name="totalBytesPerSession">キャプチャ出力の最大サイズ。</param>
        <param name="timeLimitInSeconds">秒単位でキャプチャ セッションの最大期間です。</param>
        <param name="filters">To be added.</param>
        <param name="provisioningState">パケット キャプチャ セッションのプロビジョニングの状態。 使用可能な値が含まれます: '成功'、'更新'、'削除'、'失敗'</param>
        <summary>
            PacketCaptureResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BytesToCapturePerPacket">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BytesToCapturePerPacket { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BytesToCapturePerPacket" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.BytesToCapturePerPacket" />
      <MemberSignature Language="VB.NET" Value="Public Property BytesToCapturePerPacket As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BytesToCapturePerPacket : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.BytesToCapturePerPacket" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bytesToCapturePerPacket")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パケットごとに取得するバイト数を取得または残りのバイトが切り捨てられます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; Filters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Filters" />
      <MemberSignature Language="VB.NET" Value="Public Property Filters As IList(Of PacketCaptureFilter)" />
      <MemberSignature Language="F#" Value="member this.Filters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Filters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.filters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.PacketCaptureFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パケット キャプチャ操作の ID を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            パケット キャプチャ セッションの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはパケット キャプチャ セッションのプロビジョニングの状態を設定します。
            使用可能な値が含まれます: '成功'、'更新'、'削除'、'失敗'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation StorageLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.StorageLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageLocation As PacketCaptureStorageLocation" />
      <MemberSignature Language="F#" Value="member this.StorageLocation : Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.StorageLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PacketCaptureStorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定対象のリソースのみの VM の ID は現在サポートされています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeLimitInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeLimitInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeLimitInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TimeLimitInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeLimitInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeLimitInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TimeLimitInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeLimitInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキャプチャ セッションの最大継続時間を秒単位で設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBytesPerSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalBytesPerSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalBytesPerSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TotalBytesPerSession" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBytesPerSession As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalBytesPerSession : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PacketCaptureResult.TotalBytesPerSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalBytesPerSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはキャプチャ出力の最大サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PacketCaptureResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="packetCaptureResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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