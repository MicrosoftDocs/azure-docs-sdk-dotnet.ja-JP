<Type Name="ContentSummary" FullName="Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary">
  <TypeSignature Language="C#" Value="public class ContentSummary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContentSummary extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary" />
  <TypeSignature Language="VB.NET" Value="Public Class ContentSummary" />
  <TypeSignature Language="F#" Value="type ContentSummary = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a29fc-101">Data Lake Store コンテンツの概要情報</span><span class="sxs-lookup"><span data-stu-id="a29fc-101">Data Lake Store content summary information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContentSummary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a29fc-102">ContentSummary クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-102">Initializes a new instance of the ContentSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContentSummary (Nullable&lt;long&gt; directoryCount = null, Nullable&lt;long&gt; fileCount = null, Nullable&lt;long&gt; length = null, Nullable&lt;long&gt; spaceConsumed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; directoryCount, valuetype System.Nullable`1&lt;int64&gt; fileCount, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Nullable`1&lt;int64&gt; spaceConsumed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional directoryCount As Nullable(Of Long) = null, Optional fileCount As Nullable(Of Long) = null, Optional length As Nullable(Of Long) = null, Optional spaceConsumed As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary (directoryCount, fileCount, length, spaceConsumed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directoryCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="fileCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="spaceConsumed" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="directoryCount"><span data-ttu-id="a29fc-103">ディレクトリの数。</span><span class="sxs-lookup"><span data-stu-id="a29fc-103">the number of directories.</span></span></param>
        <param name="fileCount"><span data-ttu-id="a29fc-104">ファイルの数。</span><span class="sxs-lookup"><span data-stu-id="a29fc-104">the number of files.</span></span></param>
        <param name="length"><span data-ttu-id="a29fc-105">コンテンツで使用されるバイト数。</span><span class="sxs-lookup"><span data-stu-id="a29fc-105">the number of bytes used by the content.</span></span></param>
        <param name="spaceConsumed"><span data-ttu-id="a29fc-106">コンテンツによって消費されるディスク領域です。</span><span class="sxs-lookup"><span data-stu-id="a29fc-106">the disk space consumed by the content.</span></span></param>
        <summary>
            <span data-ttu-id="a29fc-107">ContentSummary クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-107">Initializes a new instance of the ContentSummary class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DirectoryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DirectoryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DirectoryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.DirectoryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DirectoryCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DirectoryCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.DirectoryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="directoryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a29fc-108">ディレクトリの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-108">Gets the number of directories.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; FileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.FileCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a29fc-109">ファイルの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-109">Gets the number of files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Length : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a29fc-110">コンテンツで使用されるバイト数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-110">Gets the number of bytes used by the content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpaceConsumed">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SpaceConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SpaceConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.SpaceConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SpaceConsumed As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SpaceConsumed : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.DataLake.Store.Models.ContentSummary.SpaceConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="spaceConsumed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a29fc-111">コンテンツによって消費されるディスク領域を取得します。</span><span class="sxs-lookup"><span data-stu-id="a29fc-111">Gets the disk space consumed by the content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>