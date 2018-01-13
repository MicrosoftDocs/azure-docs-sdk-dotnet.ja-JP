<Type Name="RecommendedDatabaseProperties" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties">
  <TypeSignature Language="C#" Value="public class RecommendedDatabaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedDatabaseProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedDatabaseProperties" />
  <TypeSignature Language="F#" Value="type RecommendedDatabaseProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            アップグレード中、推奨される Azure SQL データベースのプロパティを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedDatabaseProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            RecommendedDatabaseProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedDatabaseProperties (string name = null, string targetEdition = null, string targetServiceLevelObjective = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string targetEdition, string targetServiceLevelObjective) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional targetEdition As String = null, Optional targetServiceLevelObjective As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties (name, targetEdition, targetServiceLevelObjective)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="targetEdition" Type="System.String" />
        <Parameter Name="targetServiceLevelObjective" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">アップグレード中、Azure SQL データベースの名前。</param>
        <param name="targetEdition">アップグレード中、Azure SQL データベースのターゲットのエディションです。 使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'</param>
        <param name="targetServiceLevelObjective">アップグレード中、Azure SQL データベースのターゲット サービス レベル目標。</param>
        <summary>
            RecommendedDatabaseProperties クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップグレード中、Azure SQL データベースの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetEdition">
      <MemberSignature Language="C#" Value="public string TargetEdition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetEdition" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetEdition As String" />
      <MemberSignature Language="F#" Value="member this.TargetEdition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップグレード中、Azure SQL データベース用のターゲットのエディションを設定します。 使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'、'無料'、'拡大'、'データ ウェアハウス'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string TargetServiceLevelObjective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.TargetServiceLevelObjective : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedDatabaseProperties.TargetServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="TargetServiceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアップグレード中、Azure SQL データベースのターゲットのサービス レベル目標を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>