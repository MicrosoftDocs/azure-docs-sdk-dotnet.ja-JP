<Type Name="StorageAccountUpdateParameters" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountUpdateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            このパラメーターは、ストレージ アカウントのプロパティを更新するときに指定することができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccountUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters (Microsoft.Azure.Management.Storage.Models.Sku sku = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Models.Identity identity = null, Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier = null, Nullable&lt;bool&gt; enableHttpsTrafficOnly = null, Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Models.Sku sku, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Models.Identity identity, class Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier, valuetype System.Nullable`1&lt;bool&gt; enableHttpsTrafficOnly, class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.#ctor(Microsoft.Azure.Management.Storage.Models.Sku,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Models.Identity,Microsoft.Azure.Management.Storage.Models.CustomDomain,Microsoft.Azure.Management.Storage.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccessTier},System.Nullable{System.Boolean},Microsoft.Azure.Management.Storage.Models.NetworkRuleSet,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters : Microsoft.Azure.Management.Storage.Models.Sku * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Models.Identity * Microsoft.Azure.Management.Storage.Models.CustomDomain * Microsoft.Azure.Management.Storage.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Storage.Models.NetworkRuleSet * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters (sku, tags, identity, customDomain, encryption, accessTier, enableHttpsTrafficOnly, networkRuleSet, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Models.Sku" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Storage.Models.Identity" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" />
        <Parameter Name="enableHttpsTrafficOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkRuleSet" Type="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="sku">取得または SKU の名前を設定します。 Standard_zrs の場合やが premium_lrs の場合に更新できません。 SKU 名もことも、sku 名のアカウントを更新してその他の値に注意してください。</param>
        <param name="tags">取得またはリソースを説明するキー値のペアの一覧を設定します。 これらのタグはリソース グループをまたがってこのリソースを表示およびグループ化する際に使用できます。 リソースの最大で 15 個のタグを指定することができます。 各タグの長さは 128 文字および超えない長さで 256 文字の値より大きくないキーが必要です。</param>
        <param name="identity">リソースの id。</param>
        <param name="customDomain">ユーザーが、ストレージ アカウントに割り当てられているカスタム ドメイン。 名前は、CNAME ソースです。 1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。 既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</param>
        <param name="encryption">アカウントの暗号化の設定を提供します。 既定の設定は暗号化されません。</param>
        <param name="accessTier">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'</param>
        <param name="enableHttpsTrafficOnly">場合にのみストレージ サービスへの https トラフィックを許可を true に設定します。</param>
        <param name="networkRuleSet">ネットワーク ルール セット</param>
        <param name="kind">省略可能。 ストレージ アカウントの種類を示します。
            現在 StorageV2 値のみサーバーでサポートされています。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'</param>
        <summary>
            StorageAccountUpdateParameters クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストレージ アカウントの種類が必要な設定を取得または BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザーによって、ストレージ アカウントに割り当てられているカスタム ドメインを設定します。 名前は、CNAME ソースです。 1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。 既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttpsTrafficOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttpsTrafficOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttpsTrafficOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.EnableHttpsTrafficOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttpsTrafficOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttpsTrafficOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.EnableHttpsTrafficOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsHttpsTrafficOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            場合に記憶域サービスのみ https トラフィックを許可するを取得または設定を true に設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、アカウントの暗号化設定を提供します。 既定の設定は暗号化されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Storage.Models.Identity with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースの id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定オプション。 ストレージ アカウントの種類を示します。
            現在 StorageV2 値のみサーバーでサポートされています。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkRuleSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.NetworkRuleSet" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkRuleSet As NetworkRuleSet" />
      <MemberSignature Language="F#" Value="member this.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.NetworkRuleSet with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.NetworkRuleSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAcls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.NetworkRuleSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ルール セットのネットワーク取得または設定
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または SKU の名前を設定します。 Standard_zrs の場合やが premium_lrs の場合に更新できません。 SKU 名もことも、sku 名のアカウントを更新してその他の値に注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースを説明するキー値のペアの一覧を設定します。
            これらのタグはリソース グループをまたがってこのリソースを表示およびグループ化する際に使用できます。 リソースの最大で 15 個のタグを指定することができます。 各タグの長さは 128 文字および超えない長さで 256 文字の値より大きくないキーが必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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