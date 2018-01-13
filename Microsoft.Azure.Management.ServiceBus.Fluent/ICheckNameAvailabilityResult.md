<Type Name="ICheckNameAvailabilityResult" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult">
  <TypeSignature Language="C#" Value="public interface ICheckNameAvailabilityResult : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckNameAvailabilityResult implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckNameAvailabilityResult&#xA;Implements IHasInner(Of CheckNameAvailabilityResultInner)" />
  <TypeSignature Language="F#" Value="type ICheckNameAvailabilityResult = interface&#xA;    interface IHasInner&lt;CheckNameAvailabilityResultInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.CheckNameAvailabilityResultInner&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Service Bus 名前空間の名前の可用性のチェックの結果。
            </summary>
    <remarks>
            (ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="IsAvailable">
      <MemberSignature Language="C#" Value="public bool IsAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.IsAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAvailable : bool" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.IsAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前が使用するために使用できるかどうかを示すブール値を取得します。 True の場合、名前は使用可能なです。 False の場合、名前は既に作成したか、無効ですされ、使用することはできません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnavailabilityMessage">
      <MemberSignature Language="C#" Value="public string UnavailabilityMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UnavailabilityMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnavailabilityMessage As String" />
      <MemberSignature Language="F#" Value="member this.UnavailabilityMessage : string" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            さらに詳しく理由の値を示すエラー メッセージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnavailabilityReason">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason UnavailabilityReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason UnavailabilityReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnavailabilityReason As UnavailableReason" />
      <MemberSignature Language="F#" Value="member this.UnavailabilityReason : Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ICheckNameAvailabilityResult.UnavailabilityReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Models.UnavailableReason</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前空間の名前が使用されないこと unavailabilityReason を取得します。 Reason 要素は NameAvailable が false の場合にのみ返されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>