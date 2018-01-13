<Type Name="ConfigureDeviceRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest">
  <TypeSignature Language="C#" Value="public class ConfigureDeviceRequest : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConfigureDeviceRequest extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfigureDeviceRequest&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type ConfigureDeviceRequest = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            必須のデバイスの構成要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigureDeviceRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ConfigureDeviceRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigureDeviceRequest (string friendlyName, string currentDeviceName, string timeZone, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings dnsSettings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings networkInterfaceData0Settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string currentDeviceName, string timeZone, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings dnsSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings networkInterfaceData0Settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest (friendlyName, currentDeviceName, timeZone, id, name, type, kind, dnsSettings, networkInterfaceData0Settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="currentDeviceName" Type="System.String" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings" />
        <Parameter Name="networkInterfaceData0Settings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings" />
      </Parameters>
      <Docs>
        <param name="friendlyName">デバイスのフレンドリ名。</param>
        <param name="currentDeviceName">デバイスの現在の名前。</param>
        <param name="timeZone">デバイスのタイム ゾーン。 例:「太平洋標準時」</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="dnsSettings">デバイスのセカンダリの DNS 設定します。</param>
        <param name="networkInterfaceData0Settings">' データ 0' のネットワーク インターフェイス カード設定します。</param>
        <summary>
            ConfigureDeviceRequest クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDeviceName">
      <MemberSignature Language="C#" Value="public string CurrentDeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentDeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.CurrentDeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentDeviceName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentDeviceName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.CurrentDeviceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDeviceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの現在の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As SecondaryDNSSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのセカンダリの DNS 設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのフレンドリ名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceData0Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings NetworkInterfaceData0Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings NetworkInterfaceData0Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.NetworkInterfaceData0Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceData0Settings As NetworkInterfaceData0Settings" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceData0Settings : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.NetworkInterfaceData0Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaceData0Settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の ' データ 0' のネットワーク インターフェイス カード設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのタイム ゾーンを設定します。 例:「太平洋標準時」
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="configureDeviceRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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