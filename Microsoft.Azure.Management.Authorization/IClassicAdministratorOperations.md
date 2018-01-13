<Type Name="IClassicAdministratorOperations" FullName="Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations">
  <TypeSignature Language="C#" Value="public interface IClassicAdministratorOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClassicAdministratorOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClassicAdministratorOperations" />
  <TypeSignature Language="F#" Value="type IClassicAdministratorOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            (詳細については http://TBD を参照してください) 従来の管理者の詳細を取得します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt; ListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt; ListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations.ListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt;" Usage="iClassicAdministratorOperations.ListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            サブスクリプションの従来の管理者の一覧を取得します。
            </summary>
        <returns>
            ClassicAdministrator 結果情報を一覧表示します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>