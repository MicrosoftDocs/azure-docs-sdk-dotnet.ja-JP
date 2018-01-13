<Type Name="InboundEndpoint" FullName="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint">
  <TypeSignature Language="C#" Value="public class InboundEndpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundEndpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundEndpoint" />
  <TypeSignature Language="F#" Value="type InboundEndpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            コンピューティング ノード上で受信エンドポイントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundEndpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            InboundEndpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundEndpoint (string name, Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, string publicIPAddress, string publicFQDN, int frontendPort, int backendPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, string publicIPAddress, string publicFQDN, int32 frontendPort, int32 backendPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol,System.String,System.String,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, publicIPAddress As String, publicFQDN As String, frontendPort As Integer, backendPort As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint : string * Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol * string * string * int * int -&gt; Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint" Usage="new Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint (name, protocol, publicIPAddress, publicFQDN, frontendPort, backendPort)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol" />
        <Parameter Name="publicIPAddress" Type="System.String" />
        <Parameter Name="publicFQDN" Type="System.String" />
        <Parameter Name="frontendPort" Type="System.Int32" />
        <Parameter Name="backendPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前。</param>
        <param name="protocol">エンドポイントのプロトコルです。</param>
        <param name="publicIPAddress">コンピューティング ノードのパブリック IP アドレス。</param>
        <param name="publicFQDN">コンピューティング ノードのパブリックの完全修飾ドメイン名です。</param>
        <param name="frontendPort">エンドポイントのパブリック ポート番号。</param>
        <param name="backendPort">エンドポイントのバックエンド ポート番号。</param>
        <summary>
            InboundEndpoint クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントのバックエンド ポート番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPort">
      <MemberSignature Language="C#" Value="public int FrontendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.FrontendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPort : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.FrontendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントのパブリック ポート番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            エンドポイントの名前を取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはエンドポイントのプロトコルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値が含まれます: 'tcp'、'udp'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicFQDN">
      <MemberSignature Language="C#" Value="public string PublicFQDN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicFQDN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.PublicFQDN" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicFQDN As String" />
      <MemberSignature Language="F#" Value="member this.PublicFQDN : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.PublicFQDN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicFQDN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードのパブリックの完全修飾ドメイン名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public string PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.PublicIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードのパブリック IP アドレスを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundEndpoint.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundEndpoint.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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