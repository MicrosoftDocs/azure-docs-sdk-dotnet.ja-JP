<Type Name="ExportRDBParametersInner" FullName="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner">
  <TypeSignature Language="C#" Value="public class ExportRDBParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportRDBParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportRDBParametersInner" />
  <TypeSignature Language="F#" Value="type ExportRDBParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f01e9-101">Redis エクスポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f01e9-101">Parameters for Redis export operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRDBParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f01e9-102">ExportRDBParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-102">Initializes a new instance of the ExportRDBParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportRDBParametersInner (string prefix, string container, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string prefix, string container, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (prefix As String, container As String, Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner : string * string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner" Usage="new Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner (prefix, container, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="prefix"><span data-ttu-id="f01e9-103">エクスポートされたファイルを使用するプレフィックス。</span><span class="sxs-lookup"><span data-stu-id="f01e9-103">Prefix to use for exported files.</span></span></param>
        <param name="container"><span data-ttu-id="f01e9-104">エクスポートするコンテナーの名前です。</span><span class="sxs-lookup"><span data-stu-id="f01e9-104">Container name to export to.</span></span></param>
        <param name="format"><span data-ttu-id="f01e9-105">ファイル形式です。</span><span class="sxs-lookup"><span data-stu-id="f01e9-105">File format.</span></span></param>
        <summary>
            <span data-ttu-id="f01e9-106">ExportRDBParametersInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-106">Initializes a new instance of the ExportRDBParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f01e9-107">取得またはエクスポートするコンテナー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-107">Gets or sets container name to export to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f01e9-108">取得またはファイルの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-108">Gets or sets file format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string with get, set" Usage="Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="f01e9-109">取得またはファイルのエクスポートに使用するプレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-109">Gets or sets prefix to use for exported files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.Models.ExportRDBParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exportRDBParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f01e9-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f01e9-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f01e9-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f01e9-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>