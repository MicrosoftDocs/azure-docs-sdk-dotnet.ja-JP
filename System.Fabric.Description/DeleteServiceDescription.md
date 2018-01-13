<Type Name="DeleteServiceDescription" FullName="System.Fabric.Description.DeleteServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class DeleteServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeleteServiceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeleteServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeleteServiceDescription" />
  <TypeSignature Language="F#" Value="type DeleteServiceDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>使用して削除する、サービスについて説明<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteServiceDescription (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeleteServiceDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeleteServiceDescription : Uri -&gt; System.Fabric.Description.DeleteServiceDescription" Usage="new System.Fabric.Description.DeleteServiceDescription serviceName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスの名前の URI。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.DeleteServiceDescription" />です。 </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceDelete">
      <MemberSignature Language="C#" Value="public bool ForceDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteServiceDescription.ForceDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceDelete : bool with get, set" Usage="System.Fabric.Description.DeleteServiceDescription.ForceDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>正常にその状態をクリーンアップして閉じるできる必要があります、サービスに指定するかどうかを指定するフラグを取得します。</para>
        </summary>
        <value>
          <para>サービスに対して、その状態と閉じるを適切にクリーンアップすることを指定してくださいかどうかを指定するフラグ。</para>
          <para>ForceDelete フラグが設定し、サービスを正常に終了しない、リークが発生するステートフルなサービスの場合は、状態を永続化されます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteServiceDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.DeleteServiceDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス インスタンスの URI 名を取得します。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>