<Type Name="IndexingMode" FullName="Microsoft.Azure.Documents.IndexingMode">
  <TypeSignature Language="C#" Value="public enum IndexingMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed IndexingMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IndexingMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum IndexingMode" />
  <TypeSignature Language="F#" Value="type IndexingMode = " />
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
            Cosmos DB の Azure サービスでサポートされているインデックス作成モードを指定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Consistent">
      <MemberSignature Language="C#" Value="Consistent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexingMode Consistent = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexingMode.Consistent" />
      <MemberSignature Language="VB.NET" Value="Consistent" />
      <MemberSignature Language="F#" Value="Consistent = 0" Usage="Microsoft.Azure.Documents.IndexingMode.Consistent" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            インデックスは、作成、更新または削除操作で同期的に更新されます。
            </summary>
        <remarks>
            一貫性のあるインデックスを使用するクエリの整合性とは、データベース アカウントの既定の一貫性レベルと同じです。 インデックスのデータを最新状態保持は常にします。
            
            既定値 IndexingMode は Consistent です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Lazy">
      <MemberSignature Language="C#" Value="Lazy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexingMode Lazy = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexingMode.Lazy" />
      <MemberSignature Language="VB.NET" Value="Lazy" />
      <MemberSignature Language="F#" Value="Lazy = 1" Usage="Microsoft.Azure.Documents.IndexingMode.Lazy" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            インデックスが作成、更新または削除操作に関して非同期的に更新されます。
            </summary>
        <remarks>
            遅延インデックスを使用するクエリは、最終的に適合しています。 全体のスループット容量 (1 秒あたりの要求単位) の下にコレクションが動作しているときに、インデックスが更新されます。 
            
            書き込み操作は、書き込み時に以下の要求単位 (RequestCharge) を消費します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.IndexingMode None = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.IndexingMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 2" Usage="Microsoft.Azure.Documents.IndexingMode.None" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexingMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            インデックスが指定されていません。
            </summary>
        <remarks>
            IndexingMode を"None"に設定は、インデックスを削除します。 ドキュメント コレクションは、記憶域のコストを節約または書き込みのスループットを向上させるインデックスを保持したくない場合は、これを使用します。 クエリは、コレクション全体のスキャンを実行する逆されます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>