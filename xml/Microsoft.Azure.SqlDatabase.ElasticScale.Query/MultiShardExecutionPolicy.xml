<Type Name="MultiShardExecutionPolicy" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy">
  <TypeSignature Language="C#" Value="public enum MultiShardExecutionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MultiShardExecutionPolicy extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Enum MultiShardExecutionPolicy" />
  <TypeSignature Language="F#" Value="type MultiShardExecutionPolicy = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fcdd4-101">使用できるクエリの実行ポリシーを定義します</span><span class="sxs-lookup"><span data-stu-id="fcdd4-101">Defines the possible query execution policies</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompleteResults">
      <MemberSignature Language="C#" Value="CompleteResults" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy CompleteResults = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.CompleteResults" />
      <MemberSignature Language="VB.NET" Value="CompleteResults" />
      <MemberSignature Language="F#" Value="CompleteResults = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.CompleteResults" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcdd4-102">完全な結果の実行ポリシーは、すべてのシャードに対して実行の失敗は、すべての結果が破棄されると、コマンドの ExecuteReader メソッドまたはリーダーの読み取りメソッドによってスローされる例外につながります。</span><span class="sxs-lookup"><span data-stu-id="fcdd4-102">With the complete results execution policy an unsuccessful execution against any shard leads to all results being discarded and an exception being thrown either by the ExecuteReader method on the command or the Read method on the reader.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialResults">
      <MemberSignature Language="C#" Value="PartialResults" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy PartialResults = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.PartialResults" />
      <MemberSignature Language="VB.NET" Value="PartialResults" />
      <MemberSignature Language="F#" Value="PartialResults = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy.PartialResults" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcdd4-103">ベスト エフォートいる実行ポリシー、CompleteResults とは異なり一部 (すべてではない) のシャードに失敗したコマンドの実行を許容し、成功したコマンドの結果を返します。</span><span class="sxs-lookup"><span data-stu-id="fcdd4-103">A best-effort execution policy that, unlike CompleteResults, tolerates unsuccessful command execution on some (but not all) shards and returns the results of the successful commands.</span></span>  
            <span data-ttu-id="fcdd4-104">部分的な結果と共にユーザーには、発生したエラーが返されます。</span><span class="sxs-lookup"><span data-stu-id="fcdd4-104">Any errors encountered are returned to the user along with the partial results.</span></span>
            <span data-ttu-id="fcdd4-105">呼び出し元を実行中に発生した例外を検査、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" />プロパティ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />です。</span><span class="sxs-lookup"><span data-stu-id="fcdd4-105">The caller can inspect exceptions encountered during execution through the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> property of <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>