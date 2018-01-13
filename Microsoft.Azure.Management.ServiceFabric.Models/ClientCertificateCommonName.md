<Type Name="ClientCertificateCommonName" FullName="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName">
  <TypeSignature Language="C#" Value="public class ClientCertificateCommonName" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientCertificateCommonName extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientCertificateCommonName" />
  <TypeSignature Language="F#" Value="type ClientCertificateCommonName = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            共通名を使用してクライアント証明書の詳細
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateCommonName ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ClientCertificateCommonName クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCertificateCommonName (bool isAdmin, string certificateCommonName, string certificateIssuerThumbprint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool isAdmin, string certificateCommonName, string certificateIssuerThumbprint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.#ctor(System.Boolean,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (isAdmin As Boolean, certificateCommonName As String, certificateIssuerThumbprint As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName : bool * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName (isAdmin, certificateCommonName, certificateIssuerThumbprint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isAdmin" Type="System.Boolean" />
        <Parameter Name="certificateCommonName" Type="System.String" />
        <Parameter Name="certificateIssuerThumbprint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isAdmin">False の場合、使用されている場合に、クライアントから管理アクセスに使用される証明書やクエリのみにアクセスします。</param>
        <param name="certificateCommonName">アクセスを許可する証明書の共通名carefull ワイルド カードの共通名を使用します。</param>
        <param name="certificateIssuerThumbprint">証明書発行者の拇印</param>
        <summary>
            ClientCertificateCommonName クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateCommonName">
      <MemberSignature Language="C#" Value="public string CertificateCommonName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateCommonName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateCommonName" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateCommonName As String" />
      <MemberSignature Language="F#" Value="member this.CertificateCommonName : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateCommonName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateCommonName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定へのアクセスを許可する証明書の共通名carefull ワイルド カードの共通名を使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateIssuerThumbprint">
      <MemberSignature Language="C#" Value="public string CertificateIssuerThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateIssuerThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateIssuerThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateIssuerThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertificateIssuerThumbprint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.CertificateIssuerThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateIssuerThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書発行者の拇印を設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public bool IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : bool with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クライアントからの管理者のアクセスに使用されるこの証明書を取得または設定は、false、使用されるかを照会する場合にのみアクセス
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clientCertificateCommonName.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
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