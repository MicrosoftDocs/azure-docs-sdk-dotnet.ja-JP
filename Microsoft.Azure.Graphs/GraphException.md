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
            任意のグラフのライブラリに重点を置いた例外の基底クラス
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
            コンストラクターです。 内部例外がキャッチされ、それをラップする必要がありますは、サーバー側の問題を使用します。
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
        <param name="errorCode">一致する HTTP RFC 2616 のエラー コードが、</param>
        <param name="message"></param>
        <summary>
            コンストラクターです。 (例: 外部) は、内部例外を使用できない場合に使用します。
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
        <param name="errorCode">一致する HTTP RFC 2616 のエラー コードが、</param>
        <param name="innerException"></param>
        <param name="message"></param>
        <summary>
            コンストラクターです。 内部例外が、それをラップする必要がある場合に使用します。
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
            現在の外部接続 (または外部の実行コンテキスト) 名、呼び出し元によって設定されました。
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
            例外に関連付けられているエラー コード。
            Graph のエラー コードが tinkerpop のプロバイダーのドキュメントで説明されているは、セマンティック: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements 関連の HTTP エラー コードは RFC 2615 定義に従って全般の詳細: http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html
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
            現在の論理フレーム (最も内側の実行スコープの名前)
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
            ときに例外が、作成スローされた時点での実行に関連付けられている要求の (必要に応じて、クライアントの呼び出し元コードにより提供) 一意の識別子。
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
            例外を表示文字列に変換します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>