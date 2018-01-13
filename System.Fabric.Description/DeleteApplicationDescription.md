<Type Name="DeleteApplicationDescription" FullName="System.Fabric.Description.DeleteApplicationDescription">
  <TypeSignature Language="C#" Value="public sealed class DeleteApplicationDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeleteApplicationDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeleteApplicationDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeleteApplicationDescription" />
  <TypeSignature Language="F#" Value="type DeleteApplicationDescription = class" />
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
      <para>使用して削除するアプリケーションについて説明<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeleteApplicationDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeleteApplicationDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeleteApplicationDescription : Uri -&gt; System.Fabric.Description.DeleteApplicationDescription" Usage="new System.Fabric.Description.DeleteApplicationDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>アプリケーション インスタンス名の URI。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.DeleteApplicationDescription" />です。 </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteApplicationDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeleteApplicationDescription.ApplicationName" />
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
          <para>アプリケーション インスタンスの URI 名を取得します。</para>
        </summary>
        <value>
          <para>アプリケーション名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceDelete">
      <MemberSignature Language="C#" Value="public bool ForceDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceDelete" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeleteApplicationDescription.ForceDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceDelete : bool with get, set" Usage="System.Fabric.Description.DeleteApplicationDescription.ForceDelete" />
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
          <para>取得または設定をその状態を正常にクリーンアップして終了できる必要があります、アプリケーションに指定するかどうかを指定するフラグ。</para>
        </summary>
        <value>
          <para>アプリケーションに対して、その状態と閉じるを適切にクリーンアップすることを指定してくださいかどうかを指定するフラグ。</para>
          <para>ForceDelete フラグ設定されている場合、アプリケーションを正常に終了しないし、リークが発生することでのステートフルなサービスの状態を永続化されます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>