<Type Name="ManagerExtendedInfo" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo">
  <TypeSignature Language="C#" Value="public class ManagerExtendedInfo : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagerExtendedInfo extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagerExtendedInfo&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type ManagerExtendedInfo = class&#xA;    inherit BaseModel" />
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
            マネージャーの拡張情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagerExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ManagerExtendedInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagerExtendedInfo (string integrityKey, string algorithm, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string version = null, string encryptionKey = null, string encryptionKeyThumbprint = null, string portalCertificateThumbprint = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string integrityKey, string algorithm, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string version, string encryptionKey, string encryptionKeyThumbprint, string portalCertificateThumbprint, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (integrityKey As String, algorithm As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional version As String = null, Optional encryptionKey As String = null, Optional encryptionKeyThumbprint As String = null, Optional portalCertificateThumbprint As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo (integrityKey, algorithm, id, name, type, kind, version, encryptionKey, encryptionKeyThumbprint, portalCertificateThumbprint, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="integrityKey" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="encryptionKey" Type="System.String" />
        <Parameter Name="encryptionKeyThumbprint" Type="System.String" />
        <Parameter Name="portalCertificateThumbprint" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="integrityKey">リソースの CIK を表します。</param>
        <param name="algorithm">キーの暗号化に使用される暗号化アルゴリズムを表します。 None - キーはプレーン テキスト形式で保存されている場合。
            アルゴリズムの名前のキーが暗号化されている場合</param>
        <param name="id">オブジェクトを一意に識別するパス ID です。</param>
        <param name="name">オブジェクトの名前。</param>
        <param name="type">オブジェクトの階層型です。</param>
        <param name="kind">オブジェクトの種類。 現在は Series8000 はサポートされています。 使用可能な値が含まれます: 'Series8000'</param>
        <param name="version">永続化される拡張情報のバージョン。</param>
        <param name="encryptionKey">リソースの CEK を表します。</param>
        <param name="encryptionKeyThumbprint">CEK の暗号化に使用された証明書の拇印を表します。</param>
        <param name="portalCertificateThumbprint">格納する前にデータ全体を暗号化するオプションで使用できるポータル拇印を表します。</param>
        <param name="etag">リソースの etag です。</param>
        <summary>
            ManagerExtendedInfo クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.algorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、キーの暗号化に使用される暗号化アルゴリズムを表します。 None - キーはプレーン テキスト形式で保存されている場合。 アルゴリズムの名前のキーが暗号化されている場合
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKey">
      <MemberSignature Language="C#" Value="public string EncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.EncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKey As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKey : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.EncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、リソースの CEK を表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyThumbprint">
      <MemberSignature Language="C#" Value="public string EncryptionKeyThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.EncryptionKeyThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.EncryptionKeyThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKeyThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、CEK の暗号化に使用された証明書の拇印を表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの etag を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrityKey">
      <MemberSignature Language="C#" Value="public string IntegrityKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IntegrityKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.IntegrityKey" />
      <MemberSignature Language="VB.NET" Value="Public Property IntegrityKey As String" />
      <MemberSignature Language="F#" Value="member this.IntegrityKey : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.IntegrityKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.integrityKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、リソースの CIK を表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PortalCertificateThumbprint">
      <MemberSignature Language="C#" Value="public string PortalCertificateThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PortalCertificateThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.PortalCertificateThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property PortalCertificateThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.PortalCertificateThumbprint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.PortalCertificateThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.portalCertificateThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を格納する前にデータ全体を暗号化するオプションで使用できるポータル拇印を表します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="managerExtendedInfo.Validate " />
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
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または保存されている拡張情報のバージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>