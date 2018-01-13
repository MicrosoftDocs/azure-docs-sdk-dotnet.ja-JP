<Type Name="ConnectivityIssue" FullName="Microsoft.Azure.Management.Network.Models.ConnectivityIssue">
  <TypeSignature Language="C#" Value="public class ConnectivityIssue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnectivityIssue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ConnectivityIssue" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnectivityIssue" />
  <TypeSignature Language="F#" Value="type ConnectivityIssue = class" />
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
            接続を確認中に発生した問題に関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor" />
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
            ConnectivityIssue クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnectivityIssue (string origin = null, string severity = null, string type = null, System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; context = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string origin, string severity, string type, class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.Collections.Generic.IDictionary{System.String,System.String}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional origin As String = null, Optional severity As String = null, Optional type As String = null, Optional context As IList(Of IDictionary(Of String, String)) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue : string * string * string * System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt; -&gt; Microsoft.Azure.Management.Network.Models.ConnectivityIssue" Usage="new Microsoft.Azure.Management.Network.Models.ConnectivityIssue (origin, severity, type, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="severity" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="context" Type="System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="origin">問題の原因です。 使用可能な値が含まれます 'Local'、'受信'、'送信'。</param>
        <param name="severity">問題の重大度。 使用可能な値が含まれます: 'Error'、'警告'</param>
        <param name="type">問題の種類。 使用可能な値が含まれます: 'Unknown'、'AgentStopped'、'GuestFirewall'、'DnsResolution'、'SocketBind'、'NetworkSecurityRule'、'UserDefinedRoute'、'PortThrottled'、'Platform'</param>
        <param name="context">問題に関する追加のコンテキストを提供します。</param>
        <summary>
            ConnectivityIssue クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string,string&gt;&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Collections.Generic.IDictionary`2&lt;string, string&gt;&gt; Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As IList(Of IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;string, string&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="context")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得は、問題に関する追加のコンテキストを提供します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            問題の発生元を取得します。 使用可能な値が含まれます 'Local'、'受信'、'送信'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public string Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As String" />
      <MemberSignature Language="F#" Value="member this.Severity : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            問題の重大度を取得します。 使用可能な値が含まれます: 'Error'、'警告'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Network.Models.ConnectivityIssue.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            問題の種類を取得します。 使用可能な値が含まれます: 'Unknown'、'AgentStopped'、'GuestFirewall'、'DnsResolution'、'SocketBind'、'NetworkSecurityRule'、'UserDefinedRoute'、'PortThrottled'、'Platform'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>