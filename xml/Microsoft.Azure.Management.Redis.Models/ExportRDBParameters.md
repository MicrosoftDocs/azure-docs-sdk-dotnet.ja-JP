<Type Name="ExportRDBParameters" FullName="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters">
  <TypeSignature Language="C#" Value="public class ExportRDBParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportRDBParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportRDBParameters" />
  <TypeSignature Language="F#" Value="type ExportRDBParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="335c2-101">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="335c2-101">Parameters for Redis export operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRDBParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="335c2-102">ExportRDBParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="335c2-102">Initializes a new instance of the ExportRDBParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRDBParameters (string prefix, string container, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string prefix, string container, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (prefix As String, container As String, Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.ExportRDBParameters : string * string * string -&gt; Microsoft.Azure.Management.Redis.Models.ExportRDBParameters" Usage="new Microsoft.Azure.Management.Redis.Models.ExportRDBParameters (prefix, container, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="335c2-103">エクスポートされたファイルを使用するプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="335c2-103">Prefix to use for exported files.</span></span></param>
        <param name="container"><span data-ttu-id="335c2-104">エクスポートするコンテナーの名前です。</span><span class="sxs-lookup"><span data-stu-id="335c2-104">Container name to export to.</span></span></param>
        <param name="format"><span data-ttu-id="335c2-105">ファイル形式です。</span><span class="sxs-lookup"><span data-stu-id="335c2-105">File format.</span></span></param>
        <summary>
            <span data-ttu-id="335c2-106">ExportRDBParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="335c2-106">Initializes a new instance of the ExportRDBParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="335c2-107">取得またはエクスポートするコンテナー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="335c2-107">Gets or sets container name to export to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="335c2-108">取得またはファイルの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="335c2-108">Gets or sets file format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="prefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="335c2-109">取得またはファイルのエクスポートに使用するプレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="335c2-109">Gets or sets prefix to use for exported files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ExportRDBParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exportRDBParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="335c2-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="335c2-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="335c2-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="335c2-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>