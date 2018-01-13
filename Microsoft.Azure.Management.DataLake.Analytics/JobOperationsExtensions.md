<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            JobOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Build">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Build (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Build(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Build(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Build (operations As IJobOperations, accountName As String, parameters As BuildJobParameters) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Build : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Build (operations, accountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="parameters">
            ジョブを作成するパラメーターです。
            </param>
        <summary>
            ジョブの正確性と検証のため、指定された Data Lake Analytics アカウントに (コンパイル)、指定されたジョブを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; BuildAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; BuildAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.BuildAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BuildAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.BuildAsync (operations, accountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;BuildAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="parameters">
            ジョブを作成するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブの正確性と検証のため、指定された Data Lake Analytics アカウントに (コンパイル)、指定されたジョブを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public static void Cancel (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Cancel(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Cancel(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Cancel (operations As IJobOperations, accountName As String, jobIdentity As Guid)" />
      <MemberSignature Language="F#" Value="static member Cancel : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Cancel (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            キャンセルする JobInfo ID です。
            </param>
        <summary>
            ジョブ ID で指定された実行中のジョブを取り消します
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CancelAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CancelAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;CancelAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            キャンセルする JobInfo ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブ ID で指定された実行中のジョブを取り消します
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Create (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Create(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Create(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobOperations, accountName As String, jobIdentity As Guid, parameters As CreateJobParameters) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Create (operations, accountName, jobIdentity, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            送信されるジョブのジョブ ID (GUID)。
            </param>
        <param name="parameters">
            ジョブを送信するパラメーターです。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントへのジョブを送信します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; CreateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; CreateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.CreateAsync (operations, accountName, jobIdentity, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;CreateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            送信されるジョブのジョブ ID (GUID)。
            </param>
        <param name="parameters">
            ジョブを送信するパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントへのジョブを送信します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Exists(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Exists (operations As IJobOperations, accountName As String, jobIdentity As Guid) As Boolean" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; bool" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Exists (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            存在をテストする JobInfo ID です。
            </param>
        <summary>
            指定したジョブ ID のジョブ情報の存在をテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ExistsAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ExistsAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            存在をテストする JobInfo ID です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブ ID のジョブ情報の存在をテストします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Get (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation Get(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobInformation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.Get (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            JobInfo id。
            </param>
        <summary>
            指定したジョブ ID のジョブ情報を取得します
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            JobInfo id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブ ID のジョブ情報を取得します
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugDataPath">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath GetDebugDataPath (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath GetDebugDataPath(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPath(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDebugDataPath (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobDataPath" />
      <MemberSignature Language="F#" Value="static member GetDebugDataPath : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPath (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            JobInfo id。
            </param>
        <summary>
            ジョブ ID で指定されたジョブのデバッグ情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDebugDataPathAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt; GetDebugDataPathAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt; GetDebugDataPathAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPathAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDebugDataPathAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetDebugDataPathAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetDebugDataPathAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            JobInfo id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブ ID で指定されたジョブのデバッグ情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics GetStatistics (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics GetStatistics(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatistics(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStatistics (operations As IJobOperations, accountName As String, jobIdentity As Guid) As JobStatistics" />
      <MemberSignature Language="F#" Value="static member GetStatistics : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatistics (operations, accountName, jobIdentity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            ジョブ情報の id。
            </param>
        <summary>
            指定されたジョブの統計情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt; GetStatisticsAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Guid jobIdentity, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt; GetStatisticsAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, valuetype System.Guid jobIdentity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatisticsAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatisticsAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.GetStatisticsAsync (operations, accountName, jobIdentity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;GetStatisticsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="jobIdentity">
            ジョブ情報の id。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブの統計情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; List (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; List(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.List(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobOperations, accountName As String, Optional odataQuery As ODataQuery(Of JobInformation) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of JobInformationBasic)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.List (operations, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListAsync (operations, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="accountName">
            ジョブの操作を実行する Azure Data Lake Analytics アカウント。
            </param>
        <param name="odataQuery">
            OData の操作に適用するパラメーター。
            </param>
        <param name="select">
            OData の Select ステートメント。 各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。 省略可能。
            </param>
        <param name="count">
            応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。 省略可能。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; ListNext (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt; ListNext(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNext(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobOperations, nextPageLink As String) As IPage(Of JobInformationBasic)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IJobOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IJobOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IJobOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.JobOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。 応答には、存在する場合、結果の次のページへのリンクが含まれています。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>