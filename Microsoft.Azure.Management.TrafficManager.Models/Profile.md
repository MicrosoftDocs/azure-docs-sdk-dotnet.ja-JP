<Type Name="Profile" FullName="Microsoft.Azure.Management.TrafficManager.Models.Profile">
  <TypeSignature Language="C#" Value="public class Profile : Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Profile extends Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Profile" />
  <TypeSignature Language="VB.NET" Value="Public Class Profile&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Profile = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.TrafficManager.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Traffic Manager プロファイルを表すクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            プロファイル クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string profileStatus = null, string trafficRoutingMethod = null, Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig = null, Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string profileStatus, string trafficRoutingMethod, class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig, class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.DnsConfig,Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Models.Endpoint})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Profile : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Microsoft.Azure.Management.TrafficManager.Models.DnsConfig * Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Profile (id, name, type, location, tags, profileStatus, trafficRoutingMethod, dnsConfig, monitorConfig, endpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="profileStatus" Type="System.String" />
        <Parameter Name="trafficRoutingMethod" Type="System.String" />
        <Parameter Name="dnsConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" />
        <Parameter Name="monitorConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig" />
        <Parameter Name="endpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース Id</param>
        <param name="name">リソース名</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所</param>
        <param name="tags">リソース タグ</param>
        <param name="profileStatus">取得または Traffic Manager プロファイルの状態を設定します。  指定できる値は、'Enabled' および '無効' には。</param>
        <param name="trafficRoutingMethod">取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。  使用可能な値は 'パフォーマンス'、'調整値'、'Priority' または '地理' です。</param>
        <param name="dnsConfig">取得または Traffic Manager プロファイルの DNS 設定を設定します。</param>
        <param name="monitorConfig">取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。</param>
        <param name="endpoints">取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。</param>
        <summary>
            プロファイル クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsConfig As DnsConfig" />
      <MemberSignature Language="F#" Value="member this.DnsConfig : Microsoft.Azure.Management.TrafficManager.Models.DnsConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DnsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager プロファイルの DNS 設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As IList(Of Endpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager プロファイルでエンドポイントのリストを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitorConfig As MonitorConfig" />
      <MemberSignature Language="F#" Value="member this.MonitorConfig : Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitorConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、エンドポイントの Traffic Manager プロファイルの設定を監視します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileStatus">
      <MemberSignature Language="C#" Value="public string ProfileStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profileStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager プロファイルの状態を設定します。  指定できる値は、'Enabled' および '無効' には。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public string TrafficRoutingMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficRoutingMethod As String" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficRoutingMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager プロファイルのトラフィック ルーティング方法を設定します。  使用可能な値は 'パフォーマンス'、'調整値'、'Priority' または '地理' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>