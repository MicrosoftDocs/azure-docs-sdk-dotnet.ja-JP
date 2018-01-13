<Type Name="VerificationIPFlowParameters" FullName="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowParameters" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            検証する IP フローを定義するパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.#ctor" />
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
            VerificationIPFlowParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowParameters (string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string direction, string protocol, string localPort, string remotePort, string localIPAddress, string remoteIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, direction As String, protocol As String, localPort As String, remotePort As String, localIPAddress As String, remoteIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters" Usage="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters (targetResourceId, direction, protocol, localPort, remotePort, localIPAddress, remoteIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="direction" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="localPort" Type="System.String" />
        <Parameter Name="remotePort" Type="System.String" />
        <Parameter Name="localIPAddress" Type="System.String" />
        <Parameter Name="remoteIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId">次のホップを実行する対象のリソースの ID。</param>
        <param name="direction">5 組として表されるパケットの方向です。 使用可能な値が含まれます: '受信'、'送信'</param>
        <param name="protocol">検証するプロトコルです。 使用可能な値が含まれます: 'TCP'、'UDP'</param>
        <param name="localPort">ローカル ポートです。 指定できる値は、1 つの整数 (0 ~ 65535) の範囲内です。 サポート * 方向に依存する発信元ポートです。</param>
        <param name="remotePort">リモート ポート。 指定できる値は、1 つの整数 (0 ~ 65535) の範囲内です。 サポート * 方向に依存する発信元ポートです。</param>
        <param name="localIPAddress">ローカル IP アドレス。 指定できる値は、有効な IPv4 アドレスです。</param>
        <param name="remoteIPAddress">リモートの IP アドレス。 指定できる値は、有効な IPv4 アドレスです。</param>
        <param name="targetNicResourceId">NIC の id。 (VM に複数の Nic があり、ユーザーがそれらのいずれかを IP 転送が有効になっているは場合、このパラメーター指定してください。 それ以外の場合省略可能)。</param>
        <summary>
            VerificationIPFlowParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または 5 組として表されるパケットの方向を設定します。
            使用可能な値が含まれます: '受信'、'送信'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalIPAddress">
      <MemberSignature Language="C#" Value="public string LocalIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローカル IP アドレスを設定します。 指定できる値は、有効な IPv4 アドレスです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalPort">
      <MemberSignature Language="C#" Value="public string LocalPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalPort" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalPort As String" />
      <MemberSignature Language="F#" Value="member this.LocalPort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.LocalPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはローカル ポートを設定します。 指定できる値は、1 つの整数 (0 ~ 65535) の範囲内です。 サポート * 方向に依存する発信元ポートです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を検証するプロトコル。 使用可能な値が含まれます: 'TCP'、'UDP'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteIPAddress">
      <MemberSignature Language="C#" Value="public string RemoteIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemoteIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.RemoteIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemoteIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remoteIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリモートの IP アドレスを設定します。 指定できる値は、有効な IPv4 アドレスです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotePort">
      <MemberSignature Language="C#" Value="public string RemotePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemotePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemotePort" />
      <MemberSignature Language="VB.NET" Value="Public Property RemotePort As String" />
      <MemberSignature Language="F#" Value="member this.RemotePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.RemotePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="remotePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリモートのポートを設定します。 指定できる値は、1 つの整数 (0 ~ 65535) の範囲内です。 サポート * 方向に依存する発信元ポートです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、NIC の id です。 (VM に複数の Nic があり、ユーザーがそれらのいずれかを IP 転送が有効になっているは場合、このパラメーター指定してください。
            それ以外の場合省略可能)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定に対して次のホップを実行する対象のリソースの ID。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="verificationIPFlowParameters.Validate " />
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