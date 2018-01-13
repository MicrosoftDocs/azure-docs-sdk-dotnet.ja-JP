<Type Name="RoleDefinitionOperationsExtensions" FullName="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RoleDefinitionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RoleDefinitionOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult CreateOrUpdate (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult CreateOrUpdate(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String, parameters As RoleDefinitionCreateOrUpdateParameters) As RoleDefinitionCreateOrUpdateResult" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdate (operations, roleDefinitionId, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 id。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <param name="parameters">
            必須。 ロールの定義。
            </param>
        <summary>
            作成するか、ロールの定義を更新します。
            </summary>
        <returns>
            ロールの定義を作成または操作の結果を更新します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String, parameters As RoleDefinitionCreateOrUpdateParameters) As Task(Of RoleDefinitionCreateOrUpdateResult)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdateAsync (operations, roleDefinitionId, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 id。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <param name="parameters">
            必須。 ロールの定義。
            </param>
        <summary>
            作成するか、ロールの定義を更新します。
            </summary>
        <returns>
            ロールの定義を作成または操作の結果を更新します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult Delete (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult Delete(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Delete(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As RoleDefinitionDeleteResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Delete (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 id。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <summary>
            ロールの定義を削除します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を削除します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As Task(Of RoleDefinitionDeleteResult)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.DeleteAsync (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 id。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <summary>
            ロールの定義を削除します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を削除します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult Get (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult Get(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Get(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As RoleDefinitionGetResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Get (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 Id
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <summary>
            名前 (GUID) によって、ロールの定義を取得します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As Task(Of RoleDefinitionGetResult)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetAsync (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 ロール定義 Id
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <summary>
            名前 (GUID) によって、ロールの定義を取得します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult GetById (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult GetById(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetById(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IRoleDefinitionOperations, roleDefinitionId As String) As RoleDefinitionGetResult" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetById (operations, roleDefinitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 完全修飾のロール定義 Id
            </param>
        <summary>
            名前 (GUID) によって、ロールの定義を取得します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByIdAsync (operations As IRoleDefinitionOperations, roleDefinitionId As String) As Task(Of RoleDefinitionGetResult)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetByIdAsync (operations, roleDefinitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="roleDefinitionId">
            必須。 完全修飾のロール定義 Id
            </param>
        <summary>
            名前 (GUID) によって、ロールの定義を取得します。
            </summary>
        <returns>
            ロールの定義は、操作の結果を取得します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult List (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult List(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.List(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRoleDefinitionOperations, scope As String, parameters As ListDefinitionFilterParameters) As RoleDefinitionListResult" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.List (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <param name="parameters">
            省略可能。 ロール定義のフィルターを一覧表示します。
            </param>
        <summary>
            スコープで以降に適用されるすべてのロールの定義を取得します。
            AtScopeAndBelow フィルターを使用して、指定されたスコープの下の検索
            </summary>
        <returns>
            ロール定義の一覧の操作の結果。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.ListAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IRoleDefinitionOperations, scope As String, parameters As ListDefinitionFilterParameters) As Task(Of RoleDefinitionListResult)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.ListAsync (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。
            </param>
        <param name="scope">
            必須。 Scope (スコープ)
            </param>
        <param name="parameters">
            省略可能。 ロール定義のフィルターを一覧表示します。
            </param>
        <summary>
            スコープで以降に適用されるすべてのロールの定義を取得します。
            AtScopeAndBelow フィルターを使用して、指定されたスコープの下の検索
            </summary>
        <returns>
            ロール定義の一覧の操作の結果。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>