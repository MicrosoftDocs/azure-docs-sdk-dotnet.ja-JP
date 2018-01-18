<Type Name="QueryMetrics" FullName="Microsoft.Azure.Documents.QueryMetrics">
  <TypeSignature Language="C#" Value="public sealed class QueryMetrics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueryMetrics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.QueryMetrics" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueryMetrics" />
  <TypeSignature Language="F#" Value="type QueryMetrics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ee92-101">Azure Cosmos DB サービスのメトリックをクエリします。</span><span class="sxs-lookup"><span data-stu-id="1ee92-101">Query metrics in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IndexHitRatio">
      <MemberSignature Language="C#" Value="public double IndexHitRatio { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 IndexHitRatio" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.IndexHitRatio" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexHitRatio As Double" />
      <MemberSignature Language="F#" Value="member this.IndexHitRatio : double" Usage="Microsoft.Azure.Documents.QueryMetrics.IndexHitRatio" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-102">Azure Cosmos DB サービスのクエリによって、インデックスのヒット率を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-102">Gets the index hit ratio by query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Addition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.QueryMetrics operator + (Microsoft.Azure.Documents.QueryMetrics m1, Microsoft.Azure.Documents.QueryMetrics m2);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Documents.QueryMetrics op_Addition(class Microsoft.Azure.Documents.QueryMetrics m1, class Microsoft.Azure.Documents.QueryMetrics m2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.QueryMetrics.op_Addition(Microsoft.Azure.Documents.QueryMetrics,Microsoft.Azure.Documents.QueryMetrics)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Operator + (m1 As QueryMetrics, m2 As QueryMetrics) As QueryMetrics" />
      <MemberSignature Language="F#" Value="static member ( + ) : Microsoft.Azure.Documents.QueryMetrics * Microsoft.Azure.Documents.QueryMetrics -&gt; Microsoft.Azure.Documents.QueryMetrics" Usage="m1 + m2" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.QueryMetrics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="m1" Type="Microsoft.Azure.Documents.QueryMetrics" />
        <Parameter Name="m2" Type="Microsoft.Azure.Documents.QueryMetrics" />
      </Parameters>
      <Docs>
        <param name="m1"><span data-ttu-id="1ee92-103">最初の<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />インスタンス</span><span class="sxs-lookup"><span data-stu-id="1ee92-103">The first <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instance</span></span></param>
        <param name="m2"><span data-ttu-id="1ee92-104">2 番目<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />インスタンス</span><span class="sxs-lookup"><span data-stu-id="1ee92-104">The second <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instance</span></span></param>
        <summary>
            <span data-ttu-id="1ee92-105">指定した 2 つ追加<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />インスタンス</span><span class="sxs-lookup"><span data-stu-id="1ee92-105">Add two specified <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instances</span></span>
            </summary>
        <returns><span data-ttu-id="1ee92-106">新しい<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />2 つの和であるインスタンス<see cref="T:Microsoft.Azure.Documents.QueryMetrics" />インスタンス</span><span class="sxs-lookup"><span data-stu-id="1ee92-106">A new <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instance that is the sum of two <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instances</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputDocumentCount">
      <MemberSignature Language="C#" Value="public long OutputDocumentCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 OutputDocumentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.OutputDocumentCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutputDocumentCount As Long" />
      <MemberSignature Language="F#" Value="member this.OutputDocumentCount : int64" Usage="Microsoft.Azure.Documents.QueryMetrics.OutputDocumentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-107">Azure Cosmos DB サービスのクエリによって返されるドキュメントの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-107">Gets the number of documents returned by query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryEngineTimes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.QueryEngineTimes QueryEngineTimes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.QueryEngineTimes QueryEngineTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.QueryEngineTimes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryEngineTimes As QueryEngineTimes" />
      <MemberSignature Language="F#" Value="member this.QueryEngineTimes : Microsoft.Azure.Documents.QueryEngineTimes" Usage="Microsoft.Azure.Documents.QueryMetrics.QueryEngineTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.QueryEngineTimes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-108">取得、 <see cref="T:Microsoft.Azure.Documents.QueryEngineTimes" /> Azure Cosmos DB サービスのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ee92-108">Gets the <see cref="T:Microsoft.Azure.Documents.QueryEngineTimes" /> instance in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryPreparationTimes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.QueryPreparationTimes QueryPreparationTimes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.QueryPreparationTimes QueryPreparationTimes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.QueryPreparationTimes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryPreparationTimes As QueryPreparationTimes" />
      <MemberSignature Language="F#" Value="member this.QueryPreparationTimes : Microsoft.Azure.Documents.QueryPreparationTimes" Usage="Microsoft.Azure.Documents.QueryMetrics.QueryPreparationTimes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.QueryPreparationTimes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-109">取得、 <see cref="T:Microsoft.Azure.Documents.QueryPreparationTimes" /> Azure Cosmos DB サービスのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ee92-109">Gets the <see cref="T:Microsoft.Azure.Documents.QueryPreparationTimes" /> instance in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retries">
      <MemberSignature Language="C#" Value="public long Retries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Retries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.Retries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retries As Long" />
      <MemberSignature Language="F#" Value="member this.Retries : int64" Usage="Microsoft.Azure.Documents.QueryMetrics.Retries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-110">Azure Cosmos DB サービス reties の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-110">Gets the number of reties in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrievedDocumentCount">
      <MemberSignature Language="C#" Value="public long RetrievedDocumentCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetrievedDocumentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.RetrievedDocumentCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievedDocumentCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetrievedDocumentCount : int64" Usage="Microsoft.Azure.Documents.QueryMetrics.RetrievedDocumentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-111">Azure Cosmos DB サービスのクエリ中に取得されたドキュメントの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-111">Gets the number of documents retrieved during query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrievedDocumentSize">
      <MemberSignature Language="C#" Value="public long RetrievedDocumentSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetrievedDocumentSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.RetrievedDocumentSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetrievedDocumentSize As Long" />
      <MemberSignature Language="F#" Value="member this.RetrievedDocumentSize : int64" Usage="Microsoft.Azure.Documents.QueryMetrics.RetrievedDocumentSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-112">Azure Cosmos DB サービスのクエリ中に、バイト単位で取得されたドキュメントのサイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-112">Gets the size of documents retrieved in bytes during query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.QueryMetrics.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="queryMetrics.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-113">取得、stringified <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> Azure Cosmos DB サービスのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="1ee92-113">Gets the stringified <see cref="T:Microsoft.Azure.Documents.QueryMetrics" /> instance in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTime">
      <MemberSignature Language="C#" Value="public TimeSpan TotalTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TotalTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.QueryMetrics.TotalTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TotalTime : TimeSpan" Usage="Microsoft.Azure.Documents.QueryMetrics.TotalTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ee92-114">Azure Cosmos DB サービスのクエリの合計時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ee92-114">Gets the total query time in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>