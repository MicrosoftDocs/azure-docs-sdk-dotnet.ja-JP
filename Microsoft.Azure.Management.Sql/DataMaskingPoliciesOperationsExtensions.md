<Type Name="DataMaskingPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataMaskingPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataMaskingPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataMaskingPoliciesOperationsExtensions = class" />
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
            DataMaskingPoliciesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy CreateOrUpdate (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy CreateOrUpdate(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataMaskingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String, parameters As DataMaskingPolicy) As DataMaskingPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, databaseName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" />
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
            データベースの名前。
            </param>
        <param name="parameters">
            作成またはデータ マスキング ポリシーを更新するためのパラメーター。
            </param>
        <summary>
            作成するか、データベースのデータ マスキング ポリシーの更新
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, databaseName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" />
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
            データベースの名前。
            </param>
        <param name="parameters">
            作成またはデータ マスキング ポリシーを更新するためのパラメーター。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成するか、データベースのデータ マスキング ポリシーの更新
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy Get (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy Get(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataMaskingPoliciesOperations, resourceGroupName As String, serverName As String, databaseName As String) As DataMaskingPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.Get (operations, resourceGroupName, serverName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
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
            データベースの名前。
            </param>
        <summary>
            データベース データ マスキング ポリシーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; GetAsync (this Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt; GetAsync(class Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations operations, string resourceGroupName, string serverName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;" Usage="Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.DataMaskingPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IDataMaskingPoliciesOperations" RefType="this" />
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
            データベースの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            データベース データ マスキング ポリシーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>