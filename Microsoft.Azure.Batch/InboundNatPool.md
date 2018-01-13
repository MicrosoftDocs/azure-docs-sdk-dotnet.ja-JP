<Type Name="InboundNatPool" FullName="Microsoft.Azure.Batch.InboundNatPool">
  <TypeSignature Language="C#" Value="public class InboundNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InboundNatPool extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.InboundNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Class InboundNatPool" />
  <TypeSignature Language="F#" Value="type InboundNatPool = class&#xA;    interface ITransportObjectProvider&lt;InboundNATPool&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
      <MemberSignature Language="C#" Value="public InboundNatPool (string name, Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int backendPort, int frontendPortRangeStart, int frontendPortRangeEnd, System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol protocol, int32 backendPort, int32 frontendPortRangeStart, int32 frontendPortRangeEnd, class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; networkSecurityGroupRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.InboundNatPool.#ctor(System.String,Microsoft.Azure.Batch.Common.InboundEndpointProtocol,System.Int32,System.Int32,System.Int32,System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Batch.NetworkSecurityGroupRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, protocol As InboundEndpointProtocol, backendPort As Integer, frontendPortRangeStart As Integer, frontendPortRangeEnd As Integer, Optional networkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.InboundNatPool : string * Microsoft.Azure.Batch.Common.InboundEndpointProtocol * int * int * int * System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; -&gt; Microsoft.Azure.Batch.InboundNatPool" Usage="new Microsoft.Azure.Batch.InboundNatPool (name, protocol, backendPort, frontendPortRangeStart, frontendPortRangeEnd, networkSecurityGroupRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="protocol" Type="Microsoft.Azure.Batch.Common.InboundEndpointProtocol" />
        <Parameter Name="backendPort" Type="System.Int32" />
        <Parameter Name="frontendPortRangeStart" Type="System.Int32" />
        <Parameter Name="frontendPortRangeEnd" Type="System.Int32" />
        <Parameter Name="networkSecurityGroupRules" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" />
      </Parameters>
      <Docs>
        <param name="name">エンドポイントの名前。</param>
        <param name="protocol">エンドポイントのプロトコルです。</param>
        <param name="backendPort">コンピューティング ノード上のポート番号。</param>
        <param name="frontendPortRangeStart">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最初のポート番号。</param>
        <param name="frontendPortRangeEnd">個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号。</param>
        <param name="networkSecurityGroupRules">エンドポイントに適用されるネットワーク セキュリティ グループ ルールの一覧。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.InboundNatPool" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendPort">
      <MemberSignature Language="C#" Value="public int BackendPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BackendPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendPort As Integer" />
      <MemberSignature Language="F#" Value="member this.BackendPort : int" Usage="Microsoft.Azure.Batch.InboundNatPool.BackendPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            コンピューティング ノードで、ポート番号を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、Batch プール内で一意でなければなりません。 指定できる値は 1 ~ 65535 の間は点を除いて 22、3389、29876 および 29877 についてこれらは予約されています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeEnd">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeEnd As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeEnd : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲の最後のポート番号を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            1 ~ 65534、Batch service によって予約されている 55000 50000 からポート以外で使用可能な値の範囲です。 プール内のすべての範囲は、異なる必要があり、重ねることはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendPortRangeStart">
      <MemberSignature Language="C#" Value="public int FrontendPortRangeStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 FrontendPortRangeStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FrontendPortRangeStart As Integer" />
      <MemberSignature Language="F#" Value="member this.FrontendPortRangeStart : int" Usage="Microsoft.Azure.Batch.InboundNatPool.FrontendPortRangeStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            個々 のコンピューティング ノードで、backendPort への着信アクセスを提供するために使用する外部ポートの範囲内の最初のポート番号を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            1 ~ 65534 に予約されている 55000 50000 からポート以外で使用可能な値の範囲です。 プール内のすべての範囲は、異なる必要があり、重ねることはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.InboundNatPool.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンドポイントの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            名前は、Batch プール内で一意である必要があります、文字、数字、アンダー スコア、ピリオド、およびハイフンを含めることができます。 名の先頭文字はや数、文字、数字、またはアンダー スコアで終わる必要があります 77 文字を超えることはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt; NetworkSecurityGroupRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupRules As IReadOnlyList(Of NetworkSecurityGroupRule)" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupRules : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;" Usage="Microsoft.Azure.Batch.InboundNatPool.NetworkSecurityGroupRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NetworkSecurityGroupRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンドポイントに適用されるグループの規則のネットワーク セキュリティの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プールのすべてのエンドポイント間で指定できるルールの最大数は 25 です。 ネットワーク セキュリティ グループの規則が指定されていない場合は、指定 backendPort への着信アクセスを許可する既定のルールが作成されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.InboundEndpointProtocol Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As InboundEndpointProtocol" />
      <MemberSignature Language="F#" Value="member this.Protocol : Microsoft.Azure.Batch.Common.InboundEndpointProtocol" Usage="Microsoft.Azure.Batch.InboundNatPool.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.InboundEndpointProtocol</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンドポイントのプロトコルを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>