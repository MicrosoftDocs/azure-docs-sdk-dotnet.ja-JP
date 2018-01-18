<Type Name="GraphException" FullName="Microsoft.Azure.Graphs.GraphException">
  <TypeSignature Language="C#" Value="public class GraphException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit GraphException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphException" />
  <TypeSignature Language="VB.NET" Value="Public Class GraphException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type GraphException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81cbb-101">任意のグラフのライブラリに重点を置いた例外の基底クラス</span><span class="sxs-lookup"><span data-stu-id="81cbb-101">Base class for any graph library-focused exceptions</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphException innerException, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Graphs.GraphException innerException, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphException,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerException As GraphException, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphException * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (innerException, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerException" Type="Microsoft.Azure.Graphs.GraphException" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="innerException"></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="81cbb-102">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="81cbb-102">Constructor.</span></span> <span data-ttu-id="81cbb-103">内部例外がキャッチされ、それをラップする必要がありますは、サーバー側の問題を使用します。</span><span class="sxs-lookup"><span data-stu-id="81cbb-103">Use it for server side issues when an inner exception was caught and we need to wrap it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphStatusCode errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Graphs.GraphStatusCode errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphStatusCode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As GraphStatusCode, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphStatusCode * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.Azure.Graphs.GraphStatusCode" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="81cbb-104">一致する HTTP RFC 2616 のエラー コードが、</span><span class="sxs-lookup"><span data-stu-id="81cbb-104">error code, matches HTTP RFC 2616</span></span></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="81cbb-105">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="81cbb-105">Constructor.</span></span> <span data-ttu-id="81cbb-106">(例: 外部) は、内部例外を使用できない場合に使用します。</span><span class="sxs-lookup"><span data-stu-id="81cbb-106">Use it when no inner (e.g. external) exception is available.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphStatusCode errorCode, Exception innerException, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Graphs.GraphStatusCode errorCode, class System.Exception innerException, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphStatusCode,System.Exception,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As GraphStatusCode, innerException As Exception, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphStatusCode * Exception * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (errorCode, innerException, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.Azure.Graphs.GraphStatusCode" />
        <Parameter Name="innerException" Type="System.Exception" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="81cbb-107">一致する HTTP RFC 2616 のエラー コードが、</span><span class="sxs-lookup"><span data-stu-id="81cbb-107">error code, matches HTTP RFC 2616</span></span></param>
        <param name="innerException"></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="81cbb-108">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="81cbb-108">Constructor.</span></span> <span data-ttu-id="81cbb-109">内部例外が、それをラップする必要がある場合に使用します。</span><span class="sxs-lookup"><span data-stu-id="81cbb-109">Use it when an inner exception was caught and we need to wrap it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public string Context { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.Context" />
      <MemberSignature Language="VB.NET" Value="Public Property Context As String" />
      <MemberSignature Language="F#" Value="member this.Context : string with get, set" Usage="Microsoft.Azure.Graphs.GraphException.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81cbb-110">現在の外部接続 (または外部の実行コンテキスト) 名、呼び出し元によって設定されました。</span><span class="sxs-lookup"><span data-stu-id="81cbb-110">Current external connection (or external execution context) name, as set by the caller</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.GraphStatusCode ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Graphs.GraphStatusCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As GraphStatusCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.Azure.Graphs.GraphStatusCode with get, set" Usage="Microsoft.Azure.Graphs.GraphException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81cbb-111">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="81cbb-111">Error code associated with the exception.</span></span>
            <span data-ttu-id="81cbb-112">Graph のエラー コードが tinkerpop のプロバイダーのドキュメントで説明されているは、セマンティック: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements 関連の HTTP エラー コードは RFC 2615 定義に従って全般の詳細: http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html</span><span class="sxs-lookup"><span data-stu-id="81cbb-112">Semantic for graph error codes is described in tinkerpop's provider documentation: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements General detail regarding HTTP Error codes as described by RFC 2615: http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frame">
      <MemberSignature Language="C#" Value="public string Frame { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frame" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.Frame" />
      <MemberSignature Language="VB.NET" Value="Public Property Frame As String" />
      <MemberSignature Language="F#" Value="member this.Frame : string with get, set" Usage="Microsoft.Azure.Graphs.GraphException.Frame" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81cbb-113">現在の論理フレーム (最も内側の実行スコープの名前)</span><span class="sxs-lookup"><span data-stu-id="81cbb-113">Current logical frame (name of innermost execution scope)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Guid RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Guid" />
      <MemberSignature Language="F#" Value="member this.RequestId : Guid with get, set" Usage="Microsoft.Azure.Graphs.GraphException.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81cbb-114">ときに例外が、作成スローされた時点での実行に関連付けられている要求の (必要に応じて、クライアントの呼び出し元コードにより提供) 一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="81cbb-114">Unique identifier (optionally provided by the client caller code) for the request associated with the execution at the moment when the exception was created/thrown.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="graphException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81cbb-115">例外を表示文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="81cbb-115">Converts an exception to a display string.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>