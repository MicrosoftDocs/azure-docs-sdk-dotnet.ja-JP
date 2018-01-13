<Type Name="DatabaseThreatDetectionPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatabaseThreatDetectionPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatabaseThreatDetectionPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatabaseThreatDetectionPoliciesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            DatabaseThreatDetectionPoliciesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatabaseThreatDetectionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DatabaseSecurityAlertPolicy) As DatabaseSecurityAlertPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            どのデータベース脅威検出機能のポリシーが定義されているデータベースの名前。
            </param>
        <param name="parameters">
            脅威検出ポリシーのデータベースです。
            </param>
        <summary>
            作成するか、データベースの脅威の検出ポリシーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            どのデータベース脅威検出機能のポリシーが定義されているデータベースの名前。
            </param>
        <param name="parameters">
            脅威検出ポリシーのデータベースです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、データベースの脅威の検出ポリシーを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy Get (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy Get(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatabaseThreatDetectionPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As DatabaseSecurityAlertPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            どのデータベース脅威検出機能のポリシーが定義されているデータベースの名前。
            </param>
        <summary>
            データベースの脅威の検出ポリシーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DatabaseThreatDetectionPoliciesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DatabaseSecurityAlertPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDatabaseThreatDetectionPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="serverName">
            サーバーの名前。
            </param>
        <param name="databaseName">
            どのデータベース脅威検出機能のポリシーが定義されているデータベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データベースの脅威の検出ポリシーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>