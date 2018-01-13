<Type Name="StatisticsOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StatisticsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StatisticsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StatisticsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StatisticsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.StatisticsListResponse List (this Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.StatisticsListResponse List(class Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.List(Microsoft.Azure.Management.Automation.IStatisticsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.StatisticsListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStatisticsOperations, resourceGroupName As String, automationAccount As String, parameters As StatisticsListParameters) As StatisticsListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IStatisticsOperations * string * string * Microsoft.Azure.Management.Automation.Models.StatisticsListParameters -&gt; Microsoft.Azure.Management.Automation.Models.StatisticsListResponse" Usage="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.StatisticsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IStatisticsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.StatisticsListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Automation.IStatisticsOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。 リソース グループの名前
            </param>
        <param name="automationAccount">
            必須。 オートメーション アカウントの名前。
            </param>
        <param name="parameters">
            省略可能。 一覧表示操作に指定するパラメーターです。
            </param>
        <summary>
            アカウントの統計情報を取得します。  (詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)
            </summary>
        <returns>
            一覧の統計情報の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IStatisticsOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.StatisticsListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IStatisticsOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.StatisticsListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IStatisticsOperations, resourceGroupName As String, automationAccount As String, parameters As StatisticsListParameters) As Task(Of StatisticsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IStatisticsOperations * string * string * Microsoft.Azure.Management.Automation.Models.StatisticsListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.StatisticsOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.StatisticsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IStatisticsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.StatisticsListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Automation.IStatisticsOperations への参照。
            </param>
        <param name="resourceGroupName">
            必須。 リソース グループの名前
            </param>
        <param name="automationAccount">
            必須。 オートメーション アカウントの名前。
            </param>
        <param name="parameters">
            省略可能。 一覧表示操作に指定するパラメーターです。
            </param>
        <summary>
            アカウントの統計情報を取得します。  (詳細については http://aka.ms/azureautomationsdk/statisticsoperations を参照してください)
            </summary>
        <returns>
            一覧の統計情報の操作の応答モデル。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>