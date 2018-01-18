<Type Name="PageRange" FullName="Microsoft.WindowsAzure.Storage.Blob.PageRange">
  <TypeSignature Language="C#" Value="public class PageRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PageRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" />
  <TypeSignature Language="VB.NET" Value="Public Class PageRange" />
  <TypeSignature Language="F#" Value="type PageRange = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94f28-101">ページ blob 内のページの範囲を表します。</span><span class="sxs-lookup"><span data-stu-id="94f28-101">Represents a range of pages in a page blob.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PageRange (long start, long end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 start, int64 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.PageRange.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Long, end As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.PageRange : int64 * int64 -&gt; Microsoft.WindowsAzure.Storage.Blob.PageRange" Usage="new Microsoft.WindowsAzure.Storage.Blob.PageRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int64" />
        <Parameter Name="end" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="94f28-102">開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="94f28-102">The starting offset.</span></span></param>
        <param name="end"><span data-ttu-id="94f28-103">終了オフセット。</span><span class="sxs-lookup"><span data-stu-id="94f28-103">The ending offset.</span></span></param>
        <summary>
            <span data-ttu-id="94f28-104"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94f28-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.PageRange" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public long EndOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.PageRange.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndOffset As Long" />
      <MemberSignature Language="F#" Value="member this.EndOffset : int64" Usage="Microsoft.WindowsAzure.Storage.Blob.PageRange.EndOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f28-105">ページ範囲の終了オフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="94f28-105">Gets the ending offset of the page range.</span></span>
            </summary>
        <value><span data-ttu-id="94f28-106">終了オフセット。</span><span class="sxs-lookup"><span data-stu-id="94f28-106">The ending offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public long StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.PageRange.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartOffset As Long" />
      <MemberSignature Language="F#" Value="member this.StartOffset : int64" Usage="Microsoft.WindowsAzure.Storage.Blob.PageRange.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f28-107">ページ範囲の開始オフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="94f28-107">Gets the starting offset of the page range.</span></span>
            </summary>
        <value><span data-ttu-id="94f28-108">開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="94f28-108">The starting offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.PageRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pageRange.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94f28-109">ページ範囲の内容を文字列として返します。</span><span class="sxs-lookup"><span data-stu-id="94f28-109">Returns the content of the page range as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="94f28-110">ページ範囲の内容。</span><span class="sxs-lookup"><span data-stu-id="94f28-110">The content of the page range.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>