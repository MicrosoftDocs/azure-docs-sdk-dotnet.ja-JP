<Type Name="IndexBatchException" FullName="Microsoft.Azure.Search.IndexBatchException">
  <TypeSignature Language="C#" Value="public class IndexBatchException : Microsoft.Rest.Azure.CloudException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexBatchException extends Microsoft.Rest.Azure.CloudException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexBatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexBatchException&#xA;Inherits CloudException" />
  <TypeSignature Language="F#" Value="type IndexBatchException = class&#xA;    inherit CloudException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.Azure.CloudException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            部分的にのみ、インデックス作成操作が成功した場合にスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexBatchException (Microsoft.Azure.Search.Models.DocumentIndexResult documentIndexResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Search.Models.DocumentIndexResult documentIndexResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.#ctor(Microsoft.Azure.Search.Models.DocumentIndexResult)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.IndexBatchException : Microsoft.Azure.Search.Models.DocumentIndexResult -&gt; Microsoft.Azure.Search.IndexBatchException" Usage="new Microsoft.Azure.Search.IndexBatchException documentIndexResult" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="documentIndexResult" Type="Microsoft.Azure.Search.Models.DocumentIndexResult" />
      </Parameters>
      <Docs>
        <param name="documentIndexResult">インデックスの要求から逆シリアル化された応答です。</param>
        <summary>
            IndexBatchException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFailedActionsToRetry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexBatch FindFailedActionsToRetry (Microsoft.Azure.Search.Models.IndexBatch originalBatch, string keyFieldName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.IndexBatch FindFailedActionsToRetry(class Microsoft.Azure.Search.Models.IndexBatch originalBatch, string keyFieldName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.FindFailedActionsToRetry(Microsoft.Azure.Search.Models.IndexBatch,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFailedActionsToRetry (originalBatch As IndexBatch, keyFieldName As String) As IndexBatch" />
      <MemberSignature Language="F#" Value="member this.FindFailedActionsToRetry : Microsoft.Azure.Search.Models.IndexBatch * string -&gt; Microsoft.Azure.Search.Models.IndexBatch" Usage="indexBatchException.FindFailedActionsToRetry (originalBatch, keyFieldName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originalBatch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="keyFieldName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalBatch">インデックス作成を部分的に失敗したバッチです。</param>
        <param name="keyFieldName">インデックス スキーマのキー フィールドの名前。</param>
        <summary>
            失敗した特定のバッチ処理と再試行する必要がありますすべてのインデックスを検索し、新しいバッチで返します。
            </summary>
        <returns>
            特定のバッチにおいて失敗し、再試行する必要がありますからのすべてのアクションを含む新しいバッチです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFailedActionsToRetry&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; FindFailedActionsToRetry&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; originalBatch, Func&lt;T,string&gt; keySelector) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; FindFailedActionsToRetry&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; originalBatch, class System.Func`2&lt;!!T, string&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexBatchException.FindFailedActionsToRetry``1(Microsoft.Azure.Search.Models.IndexBatch{``0},System.Func{``0,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFailedActionsToRetry(Of T As Class) (originalBatch As IndexBatch(Of T), keySelector As Func(Of T, String)) As IndexBatch(Of T)" />
      <MemberSignature Language="F#" Value="member this.FindFailedActionsToRetry : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Func&lt;'T, string (requires 'T : null)&gt; -&gt; Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="indexBatchException.FindFailedActionsToRetry (originalBatch, keySelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="originalBatch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="keySelector" Type="System.Func&lt;T,System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="originalBatch">インデックス作成を部分的に失敗したバッチです。</param>
        <param name="keySelector">T 型の特定のドキュメントからキーの値を取得する、ラムダ</param>
        <summary>
            失敗した特定のバッチ処理と再試行する必要がありますすべてのインデックスを検索し、新しいバッチで返します。
            </summary>
        <returns>
            特定のバッチにおいて失敗し、再試行する必要がありますからのすべてのアクションを含む新しいバッチです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt; IndexingResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.IndexingResult&gt; IndexingResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IndexingResults As IList(Of IndexingResult)" />
      <MemberSignature Language="F#" Value="member this.IndexingResults : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;" Usage="Microsoft.Azure.Search.IndexBatchException.IndexingResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.IndexingResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            各個々 のインデックス操作のステータスを含むインデックスのバッチの結果を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>