<Type Name="StorageAccountCreateParametersInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParametersInner" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            ストレージ アカウントを作成するときに使用されるパラメーター。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            StorageAccountCreateParametersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner (Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.Sku,Microsoft.Azure.Management.Storage.Fluent.Models.Kind,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner : Microsoft.Azure.Management.Storage.Fluent.Models.Sku * Microsoft.Azure.Management.Storage.Fluent.Models.Kind * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner (sku, kind, location, tags, customDomain, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="kind" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Kind" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="sku">必須。 取得または sku の名前を設定します。</param>
        <param name="kind">必須。 ストレージ アカウントの種類を示します。
            使用可能な値が含まれます: 'Storage'、'BlobStorage'</param>
        <param name="location">必須。 取得またはリソースの場所を設定します。 これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。 その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。</param>
        <param name="tags">取得またはリソースを説明するキー値のペアの一覧を設定します。 これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。 リソースの最大で 15 個のタグを指定することができます。 各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。</param>
        <param name="customDomain">ストレージ アカウントに割り当てられているユーザーのドメイン。 名前は、CNAME ソースです。 1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。 既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。</param>
        <param name="encryption">アカウントの暗号化の設定を提供します。 アカウントの暗号化設定は変わりません指定されていない場合。 既定の設定は暗号化されません。</param>
        <param name="accessTier">ストレージ アカウントの場所の種類に必要な BlobStorage を = です。 アクセス層は、課金のために使用します。 使用可能な値が含まれます: 'ホット'、'ね'</param>
        <summary>
            StorageAccountCreateParametersInner クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはストレージ アカウントに割り当てられたユーザー ドメインを設定します。 名前は、CNAME ソースです。 1 つのカスタム ドメインは、この時点でストレージ アカウントごとにサポートされてです。 既存のカスタム ドメインをオフにするには、カスタム ドメイン名のプロパティを空の文字列を使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、アカウントの暗号化設定を提供します。 アカウントの暗号化設定は変わりません指定されていない場合。 既定の設定は暗号化されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Fluent.Models.Kind with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が必要です。 ストレージ アカウントの種類を示します。
            使用可能な値が含まれます: 'Storage'、'BlobStorage'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が必要です。 取得またはリソースの場所を設定します。
            これはサポートされているいずれかにし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。 その作成が、更新時に、同じ地理的領域を指定すると場合、要求が成功したら、リソースの地理的領域を変更できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定が必要です。 取得または sku の名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            これらのタグの表示とこのリソースをグループ化 (リソース グループ) の間で使用できます。 リソースの最大で 15 個のタグを指定することができます。 各タグは、128 文字を超える長さのキーと 256 文字を超える長さの値が必要です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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