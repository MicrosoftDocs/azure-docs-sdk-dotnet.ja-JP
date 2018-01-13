<Type Name="DnsConfig" FullName="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig">
  <TypeSignature Language="C#" Value="public class DnsConfig" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DnsConfig extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class DnsConfig" />
  <TypeSignature Language="F#" Value="type DnsConfig = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Traffic Manager プロファイルで DNS 設定を含むクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DnsConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            更新クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DnsConfig (string relativeName = null, string fqdn = null, Nullable&lt;long&gt; ttl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relativeName, string fqdn, valuetype System.Nullable`1&lt;int64&gt; ttl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.#ctor(System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional relativeName As String = null, Optional fqdn As String = null, Optional ttl As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.DnsConfig : string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" Usage="new Microsoft.Azure.Management.TrafficManager.Models.DnsConfig (relativeName, fqdn, ttl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relativeName" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
        <Parameter Name="ttl" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="relativeName">取得またはこの Traffic Manager プロファイルによって提供される相対 DNS 名を設定します。  Azure Traffic Manager が使用する DNS ドメイン名とこの値を組み合わせて、プロファイルの完全修飾ドメイン名 (FQDN) が形成されます。</param>
        <param name="fqdn">取得または Traffic Manager プロファイルの完全修飾ドメイン名 (FQDN) を設定します。  これは、Azure Traffic Manager で使用する DNS ドメインと RelativeName の連結で形成されます。</param>
        <param name="ttl">取得または設定、DNS 有効期限 (TTL)、(秒)。  これは、ローカル DNS リゾルバーおよびこの Traffic Manager プロファイルによって提供される DNS 応答をキャッシュする期間の DNS クライアントに通知します。</param>
        <summary>
            更新クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Traffic Manager プロファイルの完全修飾ドメイン名 (FQDN) を設定します。  これは、Azure Traffic Manager で使用する DNS ドメインと RelativeName の連結で形成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeName">
      <MemberSignature Language="C#" Value="public string RelativeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.RelativeName" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeName As String" />
      <MemberSignature Language="F#" Value="member this.RelativeName : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.RelativeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの Traffic Manager プロファイルによって提供される相対 DNS 名を設定します。  Azure Traffic Manager が使用する DNS ドメイン名とこの値を組み合わせて、プロファイルの完全修飾ドメイン名 (FQDN) が形成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ttl">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Ttl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Ttl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Ttl" />
      <MemberSignature Language="VB.NET" Value="Public Property Ttl As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Ttl : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig.Ttl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、DNS 有効期限 (TTL)、(秒)。  これは、ローカル DNS リゾルバーおよびこの Traffic Manager プロファイルによって提供される DNS 応答をキャッシュする期間の DNS クライアントに通知します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>