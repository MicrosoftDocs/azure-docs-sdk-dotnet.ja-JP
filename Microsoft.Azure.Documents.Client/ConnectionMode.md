<Type Name="ConnectionMode" FullName="Microsoft.Azure.Documents.Client.ConnectionMode">
  <TypeSignature Language="C#" Value="public enum ConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectionMode" />
  <TypeSignature Language="F#" Value="type ConnectionMode = " />
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
            Cosmos DB の Azure サービスに接続するときに、クライアントによって使用される接続モードを表します。
            </summary>
    <remarks>
            ダイレクトとゲートウェイの接続モードはサポートされています。 ゲートウェイは、既定値です。 
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.Protocol" />
    <example>
      <code language="c#"><![CDATA[
            DocumentClient client = new DocumentClient(endpointUri, masterKey, new ConnectionPolicy { ConnectionMode = ConnectionMode.Direct });
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Direct">
      <MemberSignature Language="C#" Value="Direct" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Direct = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
      <MemberSignature Language="VB.NET" Value="Direct" />
      <MemberSignature Language="F#" Value="Direct = 1" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            使用して Azure Cosmos DB サービス内のデータ ノードに接続する接続をダイレクトします。 初期化とキャッシュの論理アドレスのみにゲートウェイを使用して更新プログラムの更新
            </summary>
        <remarks>
            最適なパフォーマンスを直接接続を使用します。 接続できる、データの Azure Cosmos DB のクラスター ノードにポート番号の範囲を使用するか HTTPS または TCP/SSL です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateway">
      <MemberSignature Language="C#" Value="Gateway" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Gateway = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
      <MemberSignature Language="VB.NET" Value="Gateway" />
      <MemberSignature Language="F#" Value="Gateway = 0" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスをすべての要求をルーティングするのにには、Azure Cosmos DB ゲートウェイを使用します。 適切なデータのパーティションにゲートウェイのプロキシ要求します。
            </summary>
        <remarks>
            ゲートウェイの接続を使用して、ファイアウォール内での設定は許可されていない場合に直接接続します。 すべての接続は、標準の HTTPS ポート (443) によって、データベース アカウントのエンドポイントに行われます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>