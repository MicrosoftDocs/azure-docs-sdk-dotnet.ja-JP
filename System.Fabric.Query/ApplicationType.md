<Type Name="ApplicationType" FullName="System.Fabric.Query.ApplicationType">
  <TypeSignature Language="C#" Value="public sealed class ApplicationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationType" />
  <TypeSignature Language="F#" Value="type ApplicationType = class" />
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
      <para>アプリケーションの種類を表します。</para>
    </summary>
    <remarks>
      <para>
                    アプリケーションの種類は、サービスの種類の集まりで構成されているアプリケーションの分類です。
                    詳細については、この説明は<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-application-model">ドキュメント</see>です。
                </para>
      <para>
                    アプリケーションの種類には、それを含むサービスのコード パッケージなどの機能を備えたアプリケーションに必要なすべてが含まれます。 アプリケーション マニフェストも含まれています。 アプリケーションがアプリケーションの種類からインスタンス化されるときに、アプリケーションの種類に関連付けられているアプリケーション マニフェストを無効にできます。 アプリケーションを作成する前に、アプリケーションの種類をアップロードする必要があります。
                    </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationTypeDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeDefinitionKind ApplicationTypeDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeDefinitionKind As ApplicationTypeDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKind : System.Fabric.Query.ApplicationTypeDefinitionKind" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>定義の種類を取得します。</para>
        </summary>
        <value>
          <para>定義の種類の列挙で定義されている値の 1 つを含む<see cref="P:System.Fabric.Query.ApplicationType.ApplicationTypeDefinitionKind" />です。</para>
          <para>Service Fabric アプリケーションの種類を定義するユーザー userd メカニズムを指定します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションの種類名を取得します。</para>
        </summary>
        <value>
          <para>アプリケーション マニフェストで定義されているアプリケーションの種類名です。 この値は、アプリケーション タイプ バージョンと共に、アプリケーションの種類の一意の識別子を作成します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.ApplicationType.ApplicationTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーション タイプのバージョンを取得します。</para>
        </summary>
        <value>
          <para>アプリケーション マニフェストで定義されているアプリケーションの種類のバージョン。 この値は、アプリケーションの種類名と共に、アプリケーションの種類の一意の識別子を作成します。 この値を数値の値にする必要はありません。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList DefaultParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList DefaultParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.DefaultParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.ApplicationType.DefaultParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションのパラメーターの既定値を取得します。</para>
        </summary>
        <value>
          <para>アプリケーション マニフェストで定義されている既定のアプリケーション パラメーター。 アプリケーションがこのアプリケーションの種類からインスタンス化されると、これらのパラメータはオーバーライドされない限りを使用します。 インスタンス化されたアプリケーションは、このプロパティで定義されているだけでなく定義されている複数のアプリケーション パラメーターもあります。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationTypeStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationTypeStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As ApplicationTypeStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.Query.ApplicationTypeStatus" Usage="System.Fabric.Query.ApplicationType.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationTypeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションの種類のステータスを取得します。</para>
        </summary>
        <value>
          <para>列挙体で定義されている値の 1 つを含むアプリケーションの種類のステータス<see cref="M:System.Fabric.Query.ApplicationTypeStatus.#ctor" />です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.ApplicationType.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションの種類のステータスの詳細を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類のステータスの詳細。 これには、このアプリケーションの種類のプロビジョニングに関連する情報が含まれています。
            プロビジョニング、中に、進行状況に関する情報が含まれます。 失敗プロビジョニングする必要があります、これにより、エラー メッセージ。
            このフィールドは空白のままそれ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>