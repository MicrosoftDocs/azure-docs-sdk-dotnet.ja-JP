<Type Name="HDInsightPigActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity">
  <TypeSignature Language="C#" Value="public class HDInsightPigActivity : Microsoft.Azure.Management.DataFactories.Models.HDInsightActivityBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HDInsightPigActivity extends Microsoft.Azure.Management.DataFactories.Models.HDInsightActivityBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class HDInsightPigActivity&#xA;Inherits HDInsightActivityBase" />
  <TypeSignature Language="F#" Value="type HDInsightPigActivity = class&#xA;    inherit HDInsightActivityBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.HDInsightActivityBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("HDInsightPig")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a9a66-101">HDInsight 上で動作する pig アクティビティ。</span><span class="sxs-lookup"><span data-stu-id="a9a66-101">Pig activity which runs on HDInsight.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HDInsightPigActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Defines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Defines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.Defines" />
      <MemberSignature Language="VB.NET" Value="Public Property Defines As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Defines : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.Defines" />
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
            <span data-ttu-id="a9a66-102">により、Pig ジョブ要求を指定するユーザーを定義します。</span><span class="sxs-lookup"><span data-stu-id="a9a66-102">Allows user to specify defines for the Pig job request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.Script" />
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
            <span data-ttu-id="a9a66-103">ハイブ スクリプト。</span><span class="sxs-lookup"><span data-stu-id="a9a66-103">Hive script.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public string ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.ScriptLinkedService" />
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
            <span data-ttu-id="a9a66-104">ストレージのリンクされたサービスがスクリプト ファイルが存在します。</span><span class="sxs-lookup"><span data-stu-id="a9a66-104">Storage linked service where the script file is located.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public string ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As String" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.HDInsightPigActivity.ScriptPath" />
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
            <span data-ttu-id="a9a66-105">Blob ストレージ内のスクリプトへのパス。</span><span class="sxs-lookup"><span data-stu-id="a9a66-105">Path to the script in blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>