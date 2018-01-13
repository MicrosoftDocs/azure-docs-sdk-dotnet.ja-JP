<Type Name="AppServiceCertificateOrderPatchResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource">
  <TypeSignature Language="C#" Value="public class AppServiceCertificateOrderPatchResource : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceCertificateOrderPatchResource extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceCertificateOrderPatchResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrderPatchResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure で購入した証明書の順序の ARM リソースです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderPatchResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AppServiceCertificateOrderPatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceCertificateOrderPatchResource (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; certificates = null, string distinguishedName = null, string domainVerificationToken = null, Nullable&lt;int&gt; validityInYears = null, Nullable&lt;int&gt; keySize = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; productType = null, Nullable&lt;bool&gt; autoRenew = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; status = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails signedCertificate = null, string csr = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails intermediate = null, Microsoft.Azure.Management.WebSites.Models.CertificateDetails root = null, string serialNumber = null, Nullable&lt;DateTime&gt; lastCertificateIssuanceTime = null, Nullable&lt;DateTime&gt; expirationTime = null, Nullable&lt;bool&gt; isPrivateKeyExternal = null, System.Collections.Generic.IList&lt;string&gt; appServiceCertificateNotRenewableReasons = null, Nullable&lt;DateTime&gt; nextAutoRenewalTimeStamp = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; certificates, string distinguishedName, string domainVerificationToken, valuetype System.Nullable`1&lt;int32&gt; validityInYears, valuetype System.Nullable`1&lt;int32&gt; keySize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; productType, valuetype System.Nullable`1&lt;bool&gt; autoRenew, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; status, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails signedCertificate, string csr, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails intermediate, class Microsoft.Azure.Management.WebSites.Models.CertificateDetails root, string serialNumber, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastCertificateIssuanceTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expirationTime, valuetype System.Nullable`1&lt;bool&gt; isPrivateKeyExternal, class System.Collections.Generic.IList`1&lt;string&gt; appServiceCertificateNotRenewableReasons, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextAutoRenewalTimeStamp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CertificateProductType},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus},Microsoft.Azure.Management.WebSites.Models.CertificateDetails,System.String,Microsoft.Azure.Management.WebSites.Models.CertificateDetails,Microsoft.Azure.Management.WebSites.Models.CertificateDetails,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional certificates As IDictionary(Of String, AppServiceCertificate) = null, Optional distinguishedName As String = null, Optional domainVerificationToken As String = null, Optional validityInYears As Nullable(Of Integer) = null, Optional keySize As Nullable(Of Integer) = null, Optional productType As Nullable(Of CertificateProductType) = null, Optional autoRenew As Nullable(Of Boolean) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of CertificateOrderStatus) = null, Optional signedCertificate As CertificateDetails = null, Optional csr As String = null, Optional intermediate As CertificateDetails = null, Optional root As CertificateDetails = null, Optional serialNumber As String = null, Optional lastCertificateIssuanceTime As Nullable(Of DateTime) = null, Optional expirationTime As Nullable(Of DateTime) = null, Optional isPrivateKeyExternal As Nullable(Of Boolean) = null, Optional appServiceCertificateNotRenewableReasons As IList(Of String) = null, Optional nextAutoRenewalTimeStamp As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * string * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * Microsoft.Azure.Management.WebSites.Models.CertificateDetails * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource (id, name, kind, type, certificates, distinguishedName, domainVerificationToken, validityInYears, keySize, productType, autoRenew, provisioningState, status, signedCertificate, csr, intermediate, root, serialNumber, lastCertificateIssuanceTime, expirationTime, isPrivateKeyExternal, appServiceCertificateNotRenewableReasons, nextAutoRenewalTimeStamp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt;" />
        <Parameter Name="distinguishedName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
        <Parameter Name="validityInYears" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="productType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt;" />
        <Parameter Name="autoRenew" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;" />
        <Parameter Name="signedCertificate" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="csr" Type="System.String" />
        <Parameter Name="intermediate" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="root" Type="Microsoft.Azure.Management.WebSites.Models.CertificateDetails" />
        <Parameter Name="serialNumber" Type="System.String" />
        <Parameter Name="lastCertificateIssuanceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="expirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="isPrivateKeyExternal" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="appServiceCertificateNotRenewableReasons" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextAutoRenewalTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソース id です。</param>
        <param name="name">リソースの名前です。</param>
        <param name="kind">リソースの種類。</param>
        <param name="type">リソースの種類。</param>
        <param name="certificates">Key Vault シークレットの状態です。</param>
        <param name="distinguishedName">証明書の識別名。</param>
        <param name="domainVerificationToken">ドメイン検証トークンです。</param>
        <param name="validityInYears">年 (1 ~ 3 の範囲である必要があります) に含まれる期間です。</param>
        <param name="keySize">証明書のキー サイズ。</param>
        <param name="productType">製品の種類の証明書します。 使用可能な値が含まれます: 'StandardDomainValidatedSsl'、'StandardDomainValidatedWildCardSsl'</param>
        <param name="autoRenew">&lt;コード&gt;true&lt;/code&gt; 、証明書は、期限が切れたときに、自動的に更新する場合は、それ以外の場合、&lt;コード&gt;false&lt;/code&gt;。</param>
        <param name="provisioningState">証明書の順序の状態です。
            使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</param>
        <param name="status">現在の注文の状態。 使用可能な値が含まれます: 'Pendingissuance'、'発行'、'無効'、'キャンセル'、'拒否'、'Pendingrevocation'、'PendingRekey'、'未使用'、'有効期限が切れた'、'NotSubmitted'</param>
        <param name="signedCertificate">署名証明書。</param>
        <param name="csr">この順序用に作成された最後の CSR です。</param>
        <param name="intermediate">中間証明書です。</param>
        <param name="root">ルート証明書。</param>
        <param name="serialNumber">証明書の現在のシリアル番号。</param>
        <param name="lastCertificateIssuanceTime">前回の発行の証明書。</param>
        <param name="expirationTime">証明書の有効期限の時刻。</param>
        <param name="isPrivateKeyExternal">&lt;コード&gt;true&lt;/code&gt;秘密キーは、外部、それ以外の場合&lt;コード&gt;false&lt;/code&gt;です。</param>
        <param name="appServiceCertificateNotRenewableReasons">なぜアプリ サービスの証明書更新可能な時点では、現在の理由。</param>
        <param name="nextAutoRenewalTimeStamp">証明書が自動になるときのタイムスタンプが次へ を更新</param>
        <summary>
            AppServiceCertificateOrderPatchResource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateNotRenewableReasons">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppServiceCertificateNotRenewableReasons { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AppServiceCertificateNotRenewableReasons" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateNotRenewableReasons As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateNotRenewableReasons : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AppServiceCertificateNotRenewableReasons" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appServiceCertificateNotRenewableReasons")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            なぜアプリ サービスの証明書更新可能な時点では、現在の理由を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRenew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoRenew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt;、証明書は、期限が切れたときに、自動的に更新する場合は、それ以外の場合、 &amp;lt; コード&amp;gt 以外の場合は false&amp;lt。/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IDictionary(Of String, AppServiceCertificate)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceCertificate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または秘密キー コンテナーの状態を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Csr">
      <MemberSignature Language="C#" Value="public string Csr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Csr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Csr" />
      <MemberSignature Language="VB.NET" Value="Public Property Csr As String" />
      <MemberSignature Language="F#" Value="member this.Csr : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Csr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.csr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこの順序用に作成された最後の CSR を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistinguishedName">
      <MemberSignature Language="C#" Value="public string DistinguishedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DistinguishedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DistinguishedName" />
      <MemberSignature Language="VB.NET" Value="Public Property DistinguishedName As String" />
      <MemberSignature Language="F#" Value="member this.DistinguishedName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DistinguishedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.distinguishedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または識別名の証明書を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainVerificationToken">
      <MemberSignature Language="C#" Value="public string DomainVerificationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainVerificationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DomainVerificationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainVerificationToken As String" />
      <MemberSignature Language="F#" Value="member this.DomainVerificationToken : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.DomainVerificationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainVerificationToken")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ドメインの確認トークンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.expirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の有効期限の時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Intermediate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails Intermediate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails Intermediate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Intermediate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Intermediate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Intermediate : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Intermediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intermediate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            中級レベルの証明書を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyExternal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrivateKeyExternal { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrivateKeyExternal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.IsPrivateKeyExternal" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivateKeyExternal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrivateKeyExternal : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.IsPrivateKeyExternal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPrivateKeyExternal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得&amp;lt; コード&amp;gt 以外の場合は true。&amp;lt;/code&amp;gt; 秘密キーは、外部、それ以外の場合&amp;lt; コード&amp;gt 以外の場合は false&amp;lt;/code&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; KeySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.KeySize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.keySize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書のキー サイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCertificateIssuanceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastCertificateIssuanceTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastCertificateIssuanceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.LastCertificateIssuanceTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCertificateIssuanceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastCertificateIssuanceTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.LastCertificateIssuanceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastCertificateIssuanceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            前回の発行の証明書を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextAutoRenewalTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextAutoRenewalTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextAutoRenewalTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.NextAutoRenewalTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextAutoRenewalTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextAutoRenewalTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.NextAutoRenewalTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nextAutoRenewalTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書が自動更新を次にある場合に時刻スタンプの取得
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; ProductType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; ProductType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProductType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProductType As Nullable(Of CertificateProductType)" />
      <MemberSignature Language="F#" Value="member this.ProductType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProductType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.productType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateProductType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または証明書の製品の種類を設定します。 使用可能な値が含まれます: 'StandardDomainValidatedSsl'、'StandardDomainValidatedWildCardSsl'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の順序の状態を取得します。 使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Root">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails Root { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails Root" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Root" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Root As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Root : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Root" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.root")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書のルートを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serialNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書の現在のシリアル番号を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.CertificateDetails SignedCertificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.CertificateDetails SignedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SignedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignedCertificate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.SignedCertificate : Microsoft.Azure.Management.WebSites.Models.CertificateDetails" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.SignedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.signedCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            証明書に署名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of CertificateOrderStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CertificateOrderStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の注文ステータスを取得します。 使用可能な値が含まれます: 'Pendingissuance'、'発行'、'無効'、'キャンセル'、'拒否'、'Pendingrevocation'、'PendingRekey'、'未使用'、'有効期限が切れた'、'NotSubmitted'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="appServiceCertificateOrderPatchResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
    <Member MemberName="ValidityInYears">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ValidityInYears { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ValidityInYears" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ValidityInYears" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidityInYears As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ValidityInYears : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceCertificateOrderPatchResource.ValidityInYears" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.validityInYears")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または年単位 (1 ~ 3 の範囲である必要があります) で期間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>