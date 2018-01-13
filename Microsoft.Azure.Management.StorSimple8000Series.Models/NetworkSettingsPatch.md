<Type Name="NetworkSettingsPatch" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch">
  <TypeSignature Language="C#" Value="public class NetworkSettingsPatch" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSettingsPatch extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSettingsPatch" />
  <TypeSignature Language="F#" Value="type NetworkSettingsPatch = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            デバイスのネットワーク設定の更新プログラムの要求を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettingsPatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NetworkSettingsPatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSettingsPatch (Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings dnsSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList networkAdapters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch (dnsSettings, networkAdapters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings" />
        <Parameter Name="networkAdapters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList" />
      </Parameters>
      <Docs>
        <param name="dnsSettings">デバイスの DNS (ドメイン ネーム システム) 設定します。</param>
        <param name="networkAdapters">デバイスのネットワーク アダプターの一覧です。</param>
        <summary>
            NetworkSettingsPatch クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As DNSSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.DnsSettings" />
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
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DNSSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスの DNS (ドメイン ネーム システム) の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAdapters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList NetworkAdapters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.NetworkAdapters" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAdapters As NetworkAdapterList" />
      <MemberSignature Language="F#" Value="member this.NetworkAdapters : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.NetworkAdapters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAdapters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkAdapterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデバイスのネットワーク アダプターの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkSettingsPatch.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="networkSettingsPatch.Validate " />
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