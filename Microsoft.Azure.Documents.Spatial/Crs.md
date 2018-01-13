<Type Name="Crs" FullName="Microsoft.Azure.Documents.Spatial.Crs">
  <TypeSignature Language="C#" Value="public abstract class Crs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Crs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Spatial.Crs" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Crs" />
  <TypeSignature Language="F#" Value="type Crs = class" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Documents.Spatial.Converters.CrsJsonConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure Cosmos DB サービスのリファレンス システムの座標を表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Crs (Microsoft.Azure.Documents.Spatial.CrsType type);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Documents.Spatial.CrsType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.#ctor(Microsoft.Azure.Documents.Spatial.CrsType)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (type As CrsType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Spatial.Crs : Microsoft.Azure.Documents.Spatial.CrsType -&gt; Microsoft.Azure.Documents.Spatial.Crs" Usage="new Microsoft.Azure.Documents.Spatial.Crs type" />
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
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Documents.Spatial.CrsType" />
      </Parameters>
      <Docs>
        <param name="type">
            CRS を入力します。
            </param>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Spatial.Crs" /> Cosmos DB の Azure サービス内のクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As Crs" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Default" />
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
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの既定の CR を取得します。 既定の CR が付いた CRS、名前"urn: ogc:def:crs:OGC:1.3:CRS84"です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked href" />
      <MemberType>Method</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            CRS リンクします。
            </param>
        <summary>
            Cosmos DB の Azure サービスにリンクされた CRS を作成します。
            </summary>
        <returns>
            インスタンス<see cref="T:Microsoft.Azure.Documents.Spatial.Crs" />クラスです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linked">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.LinkedCrs Linked (string href, string type);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.LinkedCrs Linked(string href, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Linked(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Linked (href As String, type As String) As LinkedCrs" />
      <MemberSignature Language="F#" Value="static member Linked : string * string -&gt; Microsoft.Azure.Documents.Spatial.LinkedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Linked (href, type)" />
      <MemberType>Method</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.LinkedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="href">
            CRS リンクします。
            </param>
        <param name="type">
            CRS リンクの種類。
            </param>
        <summary>
            Cosmos DB の Azure サービスで指定される省略可能な型をリンク CRS を作成します。
            </summary>
        <returns>
            インスタンス<see cref="T:Microsoft.Azure.Documents.Spatial.Crs" />クラスです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Named">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.NamedCrs Named (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Spatial.NamedCrs Named(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Spatial.Crs.Named(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Named (name As String) As NamedCrs" />
      <MemberSignature Language="F#" Value="static member Named : string -&gt; Microsoft.Azure.Documents.Spatial.NamedCrs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Named name" />
      <MemberType>Method</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Spatial.NamedCrs</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">CR の名前です。</param>
        <summary>
            Azure Cosmos DB サービスの指定された名前を名前付きの CR を作成します。
            </summary>
        <returns>インスタンス<see cref="T:Microsoft.Azure.Documents.Spatial.Crs" />クラスです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Spatial.CrsType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.Spatial.CrsType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As CrsType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Documents.Spatial.CrsType" Usage="Microsoft.Azure.Documents.Spatial.Crs.Type" />
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
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.CrsType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービス内の CR 型を取得します。
            </summary>
        <value>
            CR の型。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unspecified">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Spatial.Crs Unspecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.Documents.Spatial.Crs Unspecified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Unspecified As Crs" />
      <MemberSignature Language="F#" Value="member this.Unspecified : Microsoft.Azure.Documents.Spatial.Crs" Usage="Microsoft.Azure.Documents.Spatial.Crs.Unspecified" />
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
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Spatial.Crs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスの「未指定」CRS を取得します。 持つ「未指定」CRS ジオメトリのために想定されることができます CRS はありません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>