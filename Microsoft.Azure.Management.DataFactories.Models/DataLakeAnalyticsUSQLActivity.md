<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            データ Lake Analytics U-SQL アクティビティ。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string script);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity : string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity script" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="script">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />プレーン テキストのスクリプトを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string scriptPath, string scriptLinkedService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scriptPath, string scriptLinkedService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (scriptPath As String, scriptLinkedService As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity (scriptPath, scriptLinkedService)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scriptPath" Type="System.String" />
        <Parameter Name="scriptLinkedService" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scriptPath">To be added.</param>
        <param name="scriptLinkedService">To be added.</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />リンクされたサービスでのスクリプトを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public string CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As String" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 U-SQL のコンパイル モード。 いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.USqlCompilationMode" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 BAUs (Big Analytics ユニット数)、またはジョブの実行に同時に使用されるノードの最大数とも呼ばれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 ユーザーを U-SQL アクティビティのパラメーターを指定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 キューされているすべてのジョブのうち、先に実行するジョブを決定します。 低い優先順位が高いほど、数値 (最小値は 0) です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 使用する U SQL エンジンのランタイムのバージョン。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 プレーン テキストの U-SQL スクリプト。 これと同時に使用できません<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />と<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public string ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 U-SQL スクリプトをホストしているリンクされたサービス。 これと同時に使用する必要がある<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public string ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As String" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            省略可能。 ScriptLinkedService の U-SQL スクリプトへのパス。 これと同時に使用する必要がある<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>