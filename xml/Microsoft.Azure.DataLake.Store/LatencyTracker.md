<Type Name="LatencyTracker" FullName="Microsoft.Azure.DataLake.Store.LatencyTracker">
  <TypeSignature Language="C#" Value="public class LatencyTracker" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LatencyTracker extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.LatencyTracker" />
  <TypeSignature Language="VB.NET" Value="Public Class LatencyTracker" />
  <TypeSignature Language="F#" Value="type LatencyTracker = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="7809f-101">1 つのエントリ、コンマで区切って:</span><span class="sxs-lookup"><span data-stu-id="7809f-101">Single entry, comma separated:</span></span>
                  1. <span data-ttu-id="7809f-102">クライアント要求 ID</span><span class="sxs-lookup"><span data-stu-id="7809f-102">Client Request ID</span></span>
                  2. <span data-ttu-id="7809f-103">待機時間 (ミリ秒単位)</span><span class="sxs-lookup"><span data-stu-id="7809f-103">latency in milliseconds</span></span>
                  3. <span data-ttu-id="7809f-104">エラー コード (要求が失敗しました)</span><span class="sxs-lookup"><span data-stu-id="7809f-104">error code(if request failed)</span></span>
                  4. <span data-ttu-id="7809f-105">操作</span><span class="sxs-lookup"><span data-stu-id="7809f-105">Operation</span></span>
                  5. <span data-ttu-id="7809f-106">要求と応答本文のサイズ (使用できる場合は 0 それ以外の場合)</span><span class="sxs-lookup"><span data-stu-id="7809f-106">Request+response body Size(if available, zero otherwise)</span></span>
                  6. <span data-ttu-id="7809f-107">ADLStoreClient (この VM のインスタンスごとの一意な番号) のインスタンス</span><span class="sxs-lookup"><span data-stu-id="7809f-107">Instance of ADLStoreClient(a unique number per instance in this VM)</span></span>
            
                 <span data-ttu-id="7809f-108">複数のエントリは、1 つの要求で指定できます。エントリは、HTTP 要求のサイズが増加するを制限する 1 つの要求を 3 つのエントリを最大の制限をセミコロンで区切られます。</span><span class="sxs-lookup"><span data-stu-id="7809f-108">Multiple entries can be on a single request.Entries will be separated by semicolons Limit max entries on a single request to three, to limit increase in HTTP request size.</span></span>
                 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LatencyTracker ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static void Disable ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Disable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.LatencyTracker.Disable" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Disable ()" />
      <MemberSignature Language="F#" Value="static member Disable : unit -&gt; unit" Usage="Microsoft.Azure.DataLake.Store.LatencyTracker.Disable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7809f-109">待機時間の追跡ツールを無効になります。</span><span class="sxs-lookup"><span data-stu-id="7809f-109">Disables the Latency tracker</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>