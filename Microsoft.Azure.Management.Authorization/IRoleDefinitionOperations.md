<Type Name="IRoleDefinitionOperations" FullName="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations">
  <TypeSignature Language="C#" Value="public interface IRoleDefinitionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRoleDefinitionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRoleDefinitionOperations" />
  <TypeSignature Language="F#" Value="type IRoleDefinitionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            未定 (詳細については http://TBD を参照してください)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync (Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync(valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.CreateOrUpdateAsync(System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;" Usage="iRoleDefinitionOperations.CreateOrUpdateAsync (roleDefinitionId, scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            ロール定義 id。
            </param>
        <param name="scope">
            Scope (スコープ)
            </param>
        <param name="parameters">
            ロールの定義。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
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
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync (Guid roleDefinitionId, string scope, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync(valuetype System.Guid roleDefinitionId, string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.DeleteAsync(System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;" Usage="iRoleDefinitionOperations.DeleteAsync (roleDefinitionId, scope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            ロール定義 id。
            </param>
        <param name="scope">
            Scope (スコープ)
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
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
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync (Guid roleDefinitionId, string scope, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync(valuetype System.Guid roleDefinitionId, string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.GetAsync(System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="iRoleDefinitionOperations.GetAsync (roleDefinitionId, scope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            ロール定義 Id
            </param>
        <param name="scope">
            Scope (スコープ)
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync (string roleDefinitionId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync(string roleDefinitionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="iRoleDefinitionOperations.GetByIdAsync (roleDefinitionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            完全修飾のロール定義 Id
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
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
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync (string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync(string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.ListAsync(System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;" Usage="iRoleDefinitionOperations.ListAsync (scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            Scope (スコープ)
            </param>
        <param name="parameters">
            ロール定義のフィルターを一覧表示します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
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