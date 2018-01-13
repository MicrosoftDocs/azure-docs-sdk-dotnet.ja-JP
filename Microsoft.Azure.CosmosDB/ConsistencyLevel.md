<Type Name="ConsistencyLevel" FullName="Microsoft.Azure.CosmosDB.ConsistencyLevel">
  <TypeSignature Language="C#" Value="public enum ConsistencyLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConsistencyLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConsistencyLevel" />
  <TypeSignature Language="F#" Value="type ConsistencyLevel = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            これらは、Azure Cosmos DB サービスによってサポートされる一貫性レベルです。
            </summary>
    <remarks>
            要求の一貫性レベルは、一致か、データベース アカウントのプロビジョニングよりも弱くなりますする必要があります。
            一貫性レベルの詳細についてを参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-consistency-levels/"</see>整合性レベルに関する記事です。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BoundedStaleness">
      <MemberSignature Language="C#" Value="BoundedStaleness" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel BoundedStaleness = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberSignature Language="VB.NET" Value="BoundedStaleness" />
      <MemberSignature Language="F#" Value="BoundedStaleness = 1" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.BoundedStaleness" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            境界のある陳腐化では、読み取りがすぎる古くなっていないことを保証します。 これは、操作 (MaxStalenessPrefix) または時刻 (MaxStalenessIntervalInSeconds) の数に基づいて構成できます。  MaxStalenessPrefix と MaxStalenessIntervalInSeconds の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.ConsistencyPolicy" />です。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ConsistentPrefix">
      <MemberSignature Language="C#" Value="ConsistentPrefix" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel ConsistentPrefix = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberSignature Language="VB.NET" Value="ConsistentPrefix" />
      <MemberSignature Language="F#" Value="ConsistentPrefix = 4" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.ConsistentPrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            ConsistentPrefix 整合性では、読み取りのギャップのすべての書き込みのいくつかのプレフィックスが返されることを保証します。
            すべての書き込みはで最終的に使用できますの読み取り。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Eventual">
      <MemberSignature Language="C#" Value="Eventual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Eventual = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberSignature Language="VB.NET" Value="Eventual" />
      <MemberSignature Language="F#" Value="Eventual = 3" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Eventual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            最終的整合性では、読み取りが書き込みのサブセットを返すことを保証します。 すべての書き込みはで最終的に使用できますの読み取り。
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="Session" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Session = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberSignature Language="VB.NET" Value="Session" />
      <MemberSignature Language="F#" Value="Session = 2" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Session" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            セッションの整合性を保証単調読み取り (、古いデータの読み取りは行わないでください新しい、古い再度)、(書き込みが順序付け) 単調の書き込みと読み取りが単一セッションの中で、書き込み (、書き込みでは、読み取りをすぐに表示)。 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Strong">
      <MemberSignature Language="C#" Value="Strong" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel Strong = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberSignature Language="VB.NET" Value="Strong" />
      <MemberSignature Language="F#" Value="Strong = 0" Usage="Microsoft.Azure.CosmosDB.ConsistencyLevel.Strong" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            読み取り操作は常に強力な一貫性の保証は、最後に書き込まれた値を返します。
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>