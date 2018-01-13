<Type Name="Sku" FullName="Microsoft.Azure.Management.Storage.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ アカウントの SKU。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.Storage.Models.SkuName name, Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier = null, string resourceType = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Models.SkuName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier, string resourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor(Microsoft.Azure.Management.Storage.Models.SkuName,System.Nullable{Microsoft.Azure.Management.Storage.Models.SkuTier},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.SKUCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.Restriction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName, Optional tier As Nullable(Of SkuTier) = null, Optional resourceType As String = null, Optional kind As Nullable(Of Kind) = null, Optional locations As IList(Of String) = null, Optional capabilities As IList(Of SKUCapability) = null, Optional restrictions As IList(Of Restriction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Sku : Microsoft.Azure.Management.Storage.Models.SkuName * Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; -&gt; Microsoft.Azure.Management.Storage.Models.Sku" Usage="new Microsoft.Azure.Management.Storage.Models.Sku (name, tier, resourceType, kind, locations, capabilities, restrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Storage.Models.SkuName" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" />
        <Parameter Name="restrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;" />
      </Parameters>
      <Docs>
        <param name="name">取得または sku の名前を設定します。 アカウントの作成に必要な更新プログラムの省略可能です。 以前のバージョンで sku 名が呼び出されたこと accountType に注意してください。 使用可能な値が含まれます: 'Standard_LRS'、'Standard_GRS'、'Standard_RAGRS'、'が ' standard_zrs の場合、'Premium_LRS'</param>
        <param name="tier">Sku レベルを取得します。 これは、SKU 名に基づきます。 使用可能な値が含まれます: 'Standard'、'Premium'</param>
        <param name="resourceType">型のリソース、通常は 'storageaccounts...' です。</param>
        <param name="kind">ストレージ アカウントの種類を示します。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'</param>
        <param name="locations">SKU がある場所の集合です。 これはサポートし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。</param>
        <param name="capabilities">ファイルの暗号化、ネットワーク acl、変更通知などを含む、指定した sku の機能の情報です。</param>
        <param name="restrictions">制限事項が原因である SKU を使用することはできません。 これは制限がない場合は、空です。</param>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As IList(Of SKUCapability)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイルの暗号化、ネットワーク acl、変更通知などを含む、指定した sku の機能の情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
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
            取得では、ストレージ アカウントの種類を示します。 使用可能な値が含まれます: 'Storage'、'StorageV2'、'BlobStorage'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SKU がある場所のセットを取得します。 これはサポートし、Azure の Geo リージョン (例: 米国西部、米国東部、東南アジアなど) を登録します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または sku の名前を設定します。 アカウントの作成に必要な更新プログラムの省略可能です。 以前のバージョンで sku 名が呼び出されたこと accountType に注意してください。 使用可能な値が含まれます: 'Standard_LRS'、'Standard_GRS'、'Standard_RAGRS'、'が ' standard_zrs の場合、'Premium_LRS'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            リソースの種類は、通常は 'storageaccounts...' を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property Restrictions As IList(Of Restriction)" />
      <MemberSignature Language="F#" Value="member this.Restrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="restrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、制限が原因である SKU を使用することはできません。
            これは制限がない場合は、空です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As Nullable(Of SkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Sku レベルを取得します。 これは、SKU 名に基づきます。 使用可能な値が含まれます: 'Standard'、'Premium'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
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