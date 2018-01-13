<Type Name="ImportRDBParameters" FullName="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters">
  <TypeSignature Language="C#" Value="public class ImportRDBParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImportRDBParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ImportRDBParameters" />
  <TypeSignature Language="F#" Value="type ImportRDBParameters = class" />
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
            <span data-ttu-id="77944-101">Redis インポート操作のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="77944-101">Parameters for Redis import operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRDBParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="77944-102">ImportRDBParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77944-102">Initializes a new instance of the ImportRDBParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImportRDBParameters (System.Collections.Generic.IList&lt;string&gt; files, string format = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; files, string format) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (files As IList(Of String), Optional format As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.ImportRDBParameters : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Redis.Models.ImportRDBParameters" Usage="new Microsoft.Azure.Management.Redis.Models.ImportRDBParameters (files, format)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="files" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="format" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="files"><span data-ttu-id="77944-103">ファイルをインポートします。</span><span class="sxs-lookup"><span data-stu-id="77944-103">files to import.</span></span></param>
        <param name="format"><span data-ttu-id="77944-104">ファイル形式です。</span><span class="sxs-lookup"><span data-stu-id="77944-104">File format.</span></span></param>
        <summary>
            <span data-ttu-id="77944-105">ImportRDBParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="77944-105">Initializes a new instance of the ImportRDBParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Files { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.Files" />
      <MemberSignature Language="VB.NET" Value="Public Property Files As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Files : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="files")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="77944-106">取得またはインポートするファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="77944-106">Gets or sets files to import.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public string Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As String" />
      <MemberSignature Language="F#" Value="member this.Format : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.Format" />
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
            <span data-ttu-id="77944-107">取得またはファイルの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="77944-107">Gets or sets file format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.ImportRDBParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="importRDBParameters.Validate " />
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
            <span data-ttu-id="77944-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="77944-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="77944-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="77944-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>