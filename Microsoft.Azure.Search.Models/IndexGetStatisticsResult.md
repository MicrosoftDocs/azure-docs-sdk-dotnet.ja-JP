<Type Name="IndexGetStatisticsResult" FullName="Microsoft.Azure.Search.Models.IndexGetStatisticsResult">
  <TypeSignature Language="C#" Value="public class IndexGetStatisticsResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexGetStatisticsResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexGetStatisticsResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexGetStatisticsResult" />
  <TypeSignature Language="F#" Value="type IndexGetStatisticsResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            指定されたインデックスの統計情報です。 統計情報を使用して、定期的に収集される、常に最新の状態にする保証はありません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexGetStatisticsResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            IndexGetStatisticsResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexGetStatisticsResult (long documentCount = 0, long storageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 documentCount, int64 storageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional documentCount As Long = 0, Optional storageSize As Long = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexGetStatisticsResult : int64 * int64 -&gt; Microsoft.Azure.Search.Models.IndexGetStatisticsResult" Usage="new Microsoft.Azure.Search.Models.IndexGetStatisticsResult (documentCount, storageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="documentCount" Type="System.Int64" />
        <Parameter Name="storageSize" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="documentCount">インデックス内のドキュメントの数。</param>
        <param name="storageSize">インデックスによって使用されたバイトの記憶域の量。</param>
        <summary>
            IndexGetStatisticsResult クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentCount">
      <MemberSignature Language="C#" Value="public long DocumentCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.DocumentCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentCount As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentCount : int64 with get, set" Usage="Microsoft.Azure.Search.Models.IndexGetStatisticsResult.DocumentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="documentCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックス内のドキュメントの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageSize">
      <MemberSignature Language="C#" Value="public long StorageSize { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StorageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.StorageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageSize As Long" />
      <MemberSignature Language="F#" Value="member this.StorageSize : int64 with get, set" Usage="Microsoft.Azure.Search.Models.IndexGetStatisticsResult.StorageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックスによって使用されたバイトの記憶域の量を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>