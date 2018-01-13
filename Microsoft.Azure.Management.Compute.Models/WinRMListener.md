<Type Name="WinRMListener" FullName="Microsoft.Azure.Management.Compute.Models.WinRMListener">
  <TypeSignature Language="C#" Value="public class WinRMListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WinRMListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.WinRMListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WinRMListener" />
  <TypeSignature Language="F#" Value="type WinRMListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プロトコルと Windows リモート管理のリスナーの拇印について説明します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            WinRMListener クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener (Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol = null, string certificateUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; protocol, string certificateUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.WinRMListener.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.ProtocolTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As Nullable(Of ProtocolTypes) = null, Optional certificateUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.WinRMListener : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.WinRMListener" Usage="new Microsoft.Azure.Management.Compute.Models.WinRMListener (protocol, certificateUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;" />
        <Parameter Name="certificateUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">リスナーのプロトコルを指定します。
            &lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;**http** &lt;br&gt;&lt;br&gt; **https**です。 使用可能な値が含まれます 'Http'、'Https'。</param>
        <param name="certificateUrl">これは、シークレットとして Key Vault にアップロードされている証明書の URL です。 参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。
            証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64 でエンコードされた証明&gt;"、&lt;br&gt; "dataType":"pfx"&lt;br&gt; "password":"&lt;pfx ファイル パスワード&gt;"&lt;br&gt;}</param>
        <summary>
            WinRMListener クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、シークレットとして Key Vault にアップロードされている証明書の URL になります。 参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。
            証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;{&amp;lt; br&amp;gt;"data":"&amp;lt;Base64 でエンコードされた証明&amp;gt;"、&amp;lt; br&amp;gt;"dataType":"pfx"&amp;lt; br&amp;gt;"password":"&amp;lt; pfx ファイル パスワード&amp;gt;"&amp;lt; br&amp;gt;}
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As Nullable(Of ProtocolTypes)" />
      <MemberSignature Language="F#" Value="member this.Protocol : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.WinRMListener.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ProtocolTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、リスナーのプロトコルを指定します。
            &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;**http** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**https**です。 使用可能な値が含まれます 'Http'、'Https'。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>