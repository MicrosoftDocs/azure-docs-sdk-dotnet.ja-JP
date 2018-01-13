<Type Name="ApplicationGatewayProbeHealthResponseMatch" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayProbeHealthResponseMatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayProbeHealthResponseMatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayProbeHealthResponseMatch" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayProbeHealthResponseMatch = class" />
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
            アプリケーション ゲートウェイ プローブ ヘルス応答と一致します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbeHealthResponseMatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.#ctor" />
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
            ApplicationGatewayProbeHealthResponseMatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbeHealthResponseMatch (string body = null, System.Collections.Generic.IList&lt;string&gt; statusCodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string body, class System.Collections.Generic.IList`1&lt;string&gt; statusCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional body As String = null, Optional statusCodes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch (body, statusCodes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="body" Type="System.String" />
        <Parameter Name="statusCodes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="body">正常性の応答に含まれる必要があります本文。 既定値は空です。</param>
        <param name="statusCodes">正常な状態コードの範囲を許可します。
            既定の正常な状態コードの範囲は、200 399 です。</param>
        <summary>
            ApplicationGatewayProbeHealthResponseMatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Body">
      <MemberSignature Language="C#" Value="public string Body { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Body" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.Body" />
      <MemberSignature Language="VB.NET" Value="Public Property Body As String" />
      <MemberSignature Language="F#" Value="member this.Body : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.Body" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="body")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常性の応答本文が含まれている必要がありますを設定します。
            既定値は空です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusCodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; StatusCodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; StatusCodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.StatusCodes" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusCodes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.StatusCodes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch.StatusCodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusCodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または異常な状態のステータス コードの許可される範囲を設定します。 既定の正常な状態コードの範囲は、200 399 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>