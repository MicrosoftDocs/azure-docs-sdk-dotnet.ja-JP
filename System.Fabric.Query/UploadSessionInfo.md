<Type Name="UploadSessionInfo" FullName="System.Fabric.Query.UploadSessionInfo">
  <TypeSignature Language="C#" Value="public sealed class UploadSessionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UploadSessionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.UploadSessionInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UploadSessionInfo" />
  <TypeSignature Language="F#" Value="type UploadSessionInfo = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60f50-101">イメージ ストアのアップロード セッションに関する情報が含まれています</span><span class="sxs-lookup"><span data-stu-id="60f50-101">Contains information about the image store upload session</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExpectedRanges">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.UploadChunkRange[] ExpectedRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.UploadChunkRange[] ExpectedRanges" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.ExpectedRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpectedRanges As UploadChunkRange()" />
      <MemberSignature Language="F#" Value="member this.ExpectedRanges : System.Fabric.Query.UploadChunkRange[]" Usage="System.Fabric.Query.UploadSessionInfo.ExpectedRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.UploadChunkRange[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="60f50-102">受信していないファイルのアップロードの範囲を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f50-102">Get the range of the uploading file that have not been received.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60f50-103">受信していないファイルのアップロードの範囲。</span><span class="sxs-lookup"><span data-stu-id="60f50-103">The range of uploading file that have not been received.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSize">
      <MemberSignature Language="C#" Value="public long FileSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FileSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.FileSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileSize As Long" />
      <MemberSignature Language="F#" Value="member this.FileSize : int64" Usage="System.Fabric.Query.UploadSessionInfo.FileSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="60f50-104">イメージ ストア ファイルのバイト単位のサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="60f50-104">Gets the size in bytes of the image store file.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60f50-105">イメージ ストア ファイルのバイト サイズ。</span><span class="sxs-lookup"><span data-stu-id="60f50-105">The size in bytes of the image store file.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifiedDate">
      <MemberSignature Language="C#" Value="public DateTime ModifiedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ModifiedDate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.ModifiedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ModifiedDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.ModifiedDate : DateTime" Usage="System.Fabric.Query.UploadSessionInfo.ModifiedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="60f50-106">ファイルが最後に変更された日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="60f50-106">Gets the date and time when the file was last modified.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60f50-107">日付と、ファイルの最終変更時刻。</span><span class="sxs-lookup"><span data-stu-id="60f50-107">The date and time when the file was last modified.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public Guid SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid SessionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As Guid" />
      <MemberSignature Language="F#" Value="member this.SessionId : Guid" Usage="System.Fabric.Query.UploadSessionInfo.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="60f50-108">アップロード セッション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="60f50-108">Gets the upload session ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60f50-109">アップロードの セッション id です。</span><span class="sxs-lookup"><span data-stu-id="60f50-109">The upload session ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreRelativePath">
      <MemberSignature Language="C#" Value="public string StoreRelativePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreRelativePath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.StoreRelativePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreRelativePath As String" />
      <MemberSignature Language="F#" Value="member this.StoreRelativePath : string" Usage="System.Fabric.Query.UploadSessionInfo.StoreRelativePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="60f50-110">ネイティブ イメージ ストアのルートから、ファイルの相対パスを取得します。</span><span class="sxs-lookup"><span data-stu-id="60f50-110">Get the relative path of the file from the native image store root.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="60f50-111">ネイティブ イメージからファイルの相対パスでは、ルートを格納します。</span><span class="sxs-lookup"><span data-stu-id="60f50-111">The relative path of the file from the native image store root.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>