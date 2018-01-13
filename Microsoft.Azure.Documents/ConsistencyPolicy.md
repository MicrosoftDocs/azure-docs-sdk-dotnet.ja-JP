<Type Name="ConsistencyPolicy" FullName="Microsoft.Azure.Documents.ConsistencyPolicy">
  <TypeSignature Language="C#" Value="public sealed class ConsistencyPolicy : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConsistencyPolicy extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ConsistencyPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConsistencyPolicy&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type ConsistencyPolicy = class&#xA;    inherit JsonSerializable" />
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
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure Cosmos DB サービスのデータベース アカウントの整合性ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConsistencyPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ConsistencyPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            Cosmos DB の Azure サービスに ConsistencyPolicy クラスの既定のコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultConsistencyLevel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ConsistencyLevel DefaultConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.ConsistencyLevel DefaultConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ConsistencyPolicy.DefaultConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultConsistencyLevel As ConsistencyLevel" />
      <MemberSignature Language="F#" Value="member this.DefaultConsistencyLevel : Microsoft.Azure.Documents.ConsistencyLevel with get, set" Usage="Microsoft.Azure.Documents.ConsistencyPolicy.DefaultConsistencyLevel" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="defaultConsistencyLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスで、既定値の一貫性レベルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStalenessIntervalInSeconds">
      <MemberSignature Language="C#" Value="public int MaxStalenessIntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxStalenessIntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ConsistencyPolicy.MaxStalenessIntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStalenessIntervalInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxStalenessIntervalInSeconds : int with get, set" Usage="Microsoft.Azure.Documents.ConsistencyPolicy.MaxStalenessIntervalInSeconds" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxIntervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            境界のある陳腐化整合性 Azure Cosmos DB サービスの用語の時間間隔で期限切れが最大です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxStalenessPrefix">
      <MemberSignature Language="C#" Value="public int MaxStalenessPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxStalenessPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ConsistencyPolicy.MaxStalenessPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxStalenessPrefix As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxStalenessPrefix : int with get, set" Usage="Microsoft.Azure.Documents.ConsistencyPolicy.MaxStalenessPrefix" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxStalenessPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            境界のある陳腐化整合性 Cosmos DB の Azure サービス内のシーケンス番号 (バージョンも呼ばれる) の条項違いで期限切れが最大です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>