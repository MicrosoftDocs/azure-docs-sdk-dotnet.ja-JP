<Type Name="InboundNATPool" FullName="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool">
  <TypeSignature Language="C#" Value="public class InboundNATPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNATPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNATPool" />
  <TypeSignature Language="F#" Value="type InboundNATPool = class" />
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
            着信 NAT プールでアドレスを特定のポートを使用できる Batch プールを外部からのノードを計算します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNATPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.#ctor" />
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
            InboundNATPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InboundNATPool (string name, Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.InboundNATPool : string * Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.InboundNATPool" Usage="new Microsoft.Azure.Batch.Protocol.Models.InboundNATPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前。</param>
        <param name="protocol">エンドポイントのプロトコルです。</param>
        <param name="backendPort">コンピューティング ノード上のポート番号。</param>
        <param name="frontendPortRangeStart">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最初のポート番号。</param>
        <param name="frontendPortRangeEnd">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号。</param>
        <param name="networkSecurityGroupRules">エンドポイントに適用されるネットワーク セキュリティ グループ ルールの一覧。</param>
        <summary>
            InboundNATPool クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.BackendPort" />
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
            取得または計算ノードで、ポート番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Batch プール内で一意でなければなりません。 指定できる値は 1 ~ 65535 の間は点を除いて 22、3389、29876 および 29877 についてこれらは予約されています。 いずれかの予約されている場合、HTTP ステータス コード 400 で失敗した要求値が提供されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            1 ~ 65534、Batch service によって予約されている 55000 50000 からポート以外で使用可能な値の範囲です。 プール内のすべての範囲は、異なる必要があり、重ねることはできません。 各範囲は、少なくとも 40 のポートを含める必要があります。 予約済みか、重複する値がある場合、要求は HTTP ステータス コード 400 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="frontendPortRangeStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最初のポート番号を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            1 ~ 65534 に予約されている 55000 50000 からポート以外で使用可能な値の範囲です。 プール内のすべての範囲は、異なる必要があり、重ねることはできません。 各範囲は、少なくとも 40 のポートを含める必要があります。 予約済みか、重複する値がある場合、要求は HTTP ステータス コード 400 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Name" />
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
        <remarks>
            名前は、Batch プール内で一意である必要があります、文字、数字、アンダー スコア、ピリオド、およびハイフンを含めることができます。 名の先頭文字はや数、文字、数字、またはアンダー スコアで終わる必要があります 77 文字を超えることはできません。  無効な値がある場合、要求は HTTP ステータス コード 400 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroupRules As IList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkSecurityGroupRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはネットワークのセキュリティの一覧をエンドポイントに適用されるグループの規則を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Batch プールのすべてのエンドポイント間で指定できるルールの最大数は 25 です。 ネットワーク セキュリティ グループの規則が指定されていない場合は、指定 backendPort への着信アクセスを許可する既定のルールが作成されます。 ネットワーク セキュリティ グループの規則の最大数を超えたかどうか、要求は HTTP ステータス コード 400 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Protocol.Models.InboundEndpointProtocol with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Protocol" />
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
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.InboundNATPool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="inboundNATPool.Validate " />
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