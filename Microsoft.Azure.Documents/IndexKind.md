<Type Name="IndexKind" FullName="Microsoft.Azure.Documents.IndexKind">
  <TypeSignature Language="C#" Value="public enum IndexKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexKind" />
  <TypeSignature Language="F#" Value="type IndexKind = " />
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
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            これらは、Azure Cosmos DB サービスのパスのインデックスを作成できるインデックスの種類です。
            </summary>
    <remarks>
            追加の詳細については、http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy を参照してください。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Hash">
      <MemberSignature Language="C#" Value="Hash" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Hash = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Hash" />
      <MemberSignature Language="VB.NET" Value="Hash" />
      <MemberSignature Language="F#" Value="Hash = 0" Usage="Microsoft.Azure.Documents.IndexKind.Hash" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            インデックス エントリは、クエリを検索してポイントを使用するハッシュされます。
            </summary>
        <remarks>
            ようにクエリを処理するために使用する: 選択 * docs d WHERE d.prop から 5 を =
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Range">
      <MemberSignature Language="C#" Value="Range" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Range = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Range" />
      <MemberSignature Language="VB.NET" Value="Range" />
      <MemberSignature Language="F#" Value="Range = 1" Usage="Microsoft.Azure.Documents.IndexKind.Range" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            インデックス エントリが並べ替えられています。 範囲のインデックスは、非等値述語の効率的な範囲スキャン クエリに対して最適化されています。
            </summary>
        <remarks>
            ようにクエリを処理するために使用できます選択 * docs d WHERE d.prop から&gt;5。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Spatial">
      <MemberSignature Language="C#" Value="Spatial" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexKind Spatial = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexKind.Spatial" />
      <MemberSignature Language="VB.NET" Value="Spatial" />
      <MemberSignature Language="F#" Value="Spatial = 2" Usage="Microsoft.Azure.Documents.IndexKind.Spatial" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.IndexKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            インデックス エントリでは、インデックス空間クエリを提供します。
            </summary>
        <remarks>
            ようにクエリを処理するために使用できます選択 * FROM Root r ST_DISTANCE({"type":"Point","coordinates":[71.0589,42.3601]}, r.location) $LE 10000 場所。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>