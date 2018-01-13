<Type Name="NameOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NameOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NameOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NameOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NameOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            NameOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INameOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INameOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INameOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INameOperations, parameters As CheckNameAvailabilityRequestParameters) As CheckNameAvailabilityResponse" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INameOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse" Usage="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INameOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            名前空間の名前。
            </param>
        <summary>
            すべての Azure サブスクリプション間、指定されたサービス名前空間の可用性を確認します。 これは、機能は、ドメイン名でサービス名前空間の名前に基づいて作成されるため便利です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INameOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INameOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INameOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INameOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INameOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="parameters">
            名前空間の名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Azure サブスクリプション間、指定されたサービス名前空間の可用性を確認します。 これは、機能は、ドメイン名でサービス名前空間の名前に基づいて作成されるため便利です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>