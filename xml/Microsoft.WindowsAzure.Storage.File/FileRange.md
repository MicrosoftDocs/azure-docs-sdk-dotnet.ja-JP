<Type Name="FileRange" FullName="Microsoft.WindowsAzure.Storage.File.FileRange">
  <TypeSignature Language="C#" Value="public sealed class FileRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileRange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileRange" />
  <TypeSignature Language="F#" Value="type FileRange = class" />
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
            <span data-ttu-id="cfd27-101">ファイル内の範囲を表します。</span><span class="sxs-lookup"><span data-stu-id="cfd27-101">Represents a range in a file.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileRange (long start, long end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 start, int64 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileRange.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Long, end As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.FileRange : int64 * int64 -&gt; Microsoft.WindowsAzure.Storage.File.FileRange" Usage="new Microsoft.WindowsAzure.Storage.File.FileRange (start, end)" />
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
        <param name="start"><span data-ttu-id="cfd27-102">開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="cfd27-102">The starting offset.</span></span></param>
        <param name="end"><span data-ttu-id="cfd27-103">終了オフセット。</span><span class="sxs-lookup"><span data-stu-id="cfd27-103">The ending offset.</span></span></param>
        <summary>
            <span data-ttu-id="cfd27-104"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cfd27-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRange" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOffset">
      <MemberSignature Language="C#" Value="public long EndOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EndOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRange.EndOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndOffset As Long" />
      <MemberSignature Language="F#" Value="member this.EndOffset : int64" Usage="Microsoft.WindowsAzure.Storage.File.FileRange.EndOffset" />
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
            <span data-ttu-id="cfd27-105">ページ範囲の終了オフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="cfd27-105">Gets the ending offset of the page range.</span></span>
            </summary>
        <value><span data-ttu-id="cfd27-106">終了オフセット。</span><span class="sxs-lookup"><span data-stu-id="cfd27-106">The ending offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="public long StartOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileRange.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartOffset As Long" />
      <MemberSignature Language="F#" Value="member this.StartOffset : int64" Usage="Microsoft.WindowsAzure.Storage.File.FileRange.StartOffset" />
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
            <span data-ttu-id="cfd27-107">ページ範囲の開始オフセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="cfd27-107">Gets the starting offset of the page range.</span></span>
            </summary>
        <value><span data-ttu-id="cfd27-108">開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="cfd27-108">The starting offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.FileRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="fileRange.ToString " />
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
            <span data-ttu-id="cfd27-109">範囲の内容を文字列として返します。</span><span class="sxs-lookup"><span data-stu-id="cfd27-109">Returns the content of the range as a string.</span></span>
            </summary>
        <returns><span data-ttu-id="cfd27-110">範囲の内容。</span><span class="sxs-lookup"><span data-stu-id="cfd27-110">The content of the range.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>