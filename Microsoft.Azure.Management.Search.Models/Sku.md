<Type Name="Sku" FullName="Microsoft.Azure.Management.Search.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            価格レベルと容量を決定する、Azure Search サービスの SKU を定義する制限。
            <see href="https://azure.microsoft.com/documentation/articles/search-sku-tier/" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Sku (Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SkuName&gt; name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.Sku.#ctor(System.Nullable{Microsoft.Azure.Management.Search.Models.SkuName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As Nullable(Of SkuName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.Sku : Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; -&gt; Microsoft.Azure.Management.Search.Models.Sku" Usage="new Microsoft.Azure.Management.Search.Models.Sku name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt;" />
      </Parameters>
      <Docs>
        <param name="name">検索サービスの SKU。 有効な値: 'free': サービスを共有します。 'basic': 最大 3 つのレプリカを使用してサービスを専用です。 'standard': 専用に最大 12 個のパーティションと 12 のレプリカでのサービスです。 'standard2': のような検索単位あたりの容量増加ですが standard にします。 'standard3': 最大 12 のパーティションと 12 のレプリカと (または 'highDensity' hostingMode プロパティに設定する場合より多くのインデックスとパーティション 3 つまで)、検索単位あたりの最大容量を提供します。 使用可能な値が含まれます: '無料'、'basic'、'standard'、'standard2'、'standard3'</param>
        <summary>
            Sku クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SkuName&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Nullable(Of SkuName)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SkuName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または検索サービスの SKU を設定します。 有効な値: 'free': サービスを共有します。 'basic': 最大 3 つのレプリカを使用してサービスを専用です。 'standard': 専用に最大 12 個のパーティションと 12 のレプリカでのサービスです。 'standard2': のような検索単位あたりの容量増加ですが standard にします。 'standard3': 最大 12 のパーティションと 12 のレプリカと (または 'highDensity' hostingMode プロパティに設定する場合より多くのインデックスとパーティション 3 つまで)、検索単位あたりの最大容量を提供します。 使用可能な値が含まれます: '無料'、'basic'、'standard'、'standard2'、'standard3'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>