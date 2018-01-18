<Type Name="HiveJobProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties">
  <TypeSignature Language="C#" Value="public class HiveJobProperties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HiveJobProperties extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class HiveJobProperties&#xA;Inherits JobProperties" />
  <TypeSignature Language="F#" Value="type HiveJobProperties = class&#xA;    inherit JobProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Hive")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="106fa-101">Hive ジョブを取得するときに使用されるジョブのプロパティを hive します。</span><span class="sxs-lookup"><span data-stu-id="106fa-101">Hive job properties used when retrieving Hive jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HiveJobProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="106fa-102">HiveJobProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="106fa-102">Initializes a new instance of the HiveJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HiveJobProperties (string script, string runtimeVersion = null, string logsLocation = null, string outputLocation = null, Nullable&lt;int&gt; statementCount = null, Nullable&lt;int&gt; executedStatementCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script, string runtimeVersion, string logsLocation, string outputLocation, valuetype System.Nullable`1&lt;int32&gt; statementCount, valuetype System.Nullable`1&lt;int32&gt; executedStatementCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String, Optional runtimeVersion As String = null, Optional logsLocation As String = null, Optional outputLocation As String = null, Optional statementCount As Nullable(Of Integer) = null, Optional executedStatementCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties (script, runtimeVersion, logsLocation, outputLocation, statementCount, executedStatementCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
        <Parameter Name="runtimeVersion" Type="System.String" />
        <Parameter Name="logsLocation" Type="System.String" />
        <Parameter Name="outputLocation" Type="System.String" />
        <Parameter Name="statementCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="executedStatementCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="script"><span data-ttu-id="106fa-103">スクリプトを実行するには</span><span class="sxs-lookup"><span data-stu-id="106fa-103">the script to run</span></span></param>
        <param name="runtimeVersion"><span data-ttu-id="106fa-104">ジョブの実行中の特定の型を使用する Data Lake Analytics エンジンのランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="106fa-104">the runtime version of the Data Lake Analytics engine to use for the specific type of job being run.</span></span></param>
        <param name="logsLocation"><span data-ttu-id="106fa-105">ハイブ ログの場所</span><span class="sxs-lookup"><span data-stu-id="106fa-105">the Hive logs location</span></span></param>
        <param name="outputLocation"><span data-ttu-id="106fa-106">Hive ジョブの出力ファイル (実行の出力と結果の両方) の場所</span><span class="sxs-lookup"><span data-stu-id="106fa-106">the location of Hive job output files (both execution output and results)</span></span></param>
        <param name="statementCount"><span data-ttu-id="106fa-107">スクリプトをに基づいて実行されるステートメントの数</span><span class="sxs-lookup"><span data-stu-id="106fa-107">the number of statements that will be run based on the script</span></span></param>
        <param name="executedStatementCount"><span data-ttu-id="106fa-108">実行されたステートメント数が、スクリプトに基づく</span><span class="sxs-lookup"><span data-stu-id="106fa-108">the number of statements that have been run based on the script</span></span></param>
        <summary>
            <span data-ttu-id="106fa-109">HiveJobProperties クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="106fa-109">Initializes a new instance of the HiveJobProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutedStatementCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExecutedStatementCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExecutedStatementCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.ExecutedStatementCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutedStatementCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExecutedStatementCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.ExecutedStatementCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="executedStatementCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106fa-110">実行されているベース スクリプト ステートメントの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="106fa-110">Gets the number of statements that have been run based on the script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogsLocation">
      <MemberSignature Language="C#" Value="public string LogsLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogsLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.LogsLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogsLocation As String" />
      <MemberSignature Language="F#" Value="member this.LogsLocation : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.LogsLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logsLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106fa-111">ハイブ ログの場所を取得します。</span><span class="sxs-lookup"><span data-stu-id="106fa-111">Gets the Hive logs location</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputLocation">
      <MemberSignature Language="C#" Value="public string OutputLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.OutputLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutputLocation As String" />
      <MemberSignature Language="F#" Value="member this.OutputLocation : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.OutputLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106fa-112">Hive ジョブの場所に出力ファイル (実行の出力と結果の両方) を取得します。</span><span class="sxs-lookup"><span data-stu-id="106fa-112">Gets the location of Hive job output files (both execution output and results)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatementCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StatementCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StatementCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.StatementCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatementCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StatementCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.StatementCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statementCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="106fa-113">スクリプト上ベースで実行されるステートメントの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="106fa-113">Gets the number of statements that will be run based on the script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.HiveJobProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="hiveJobProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="106fa-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="106fa-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="106fa-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="106fa-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>