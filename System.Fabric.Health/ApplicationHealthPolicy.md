<Type Name="ApplicationHealthPolicy" FullName="System.Fabric.Health.ApplicationHealthPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationHealthPolicy" />
  <TypeSignature Language="F#" Value="type ApplicationHealthPolicy = class" />
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
      <para>Service Fabric アプリケーションまたはその子エンティティを 1 つの正常性を評価する正常性ポリシーを定義します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>既定のアプリケーションの正常性ポリシーには、エラーまたは警告を許容しません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
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
          <para>取得または設定、<see cref="T:System.Boolean" />エラーとして重大度が同じで、警告状態を持つレポートを扱う必要があるかどうかを決定します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合は警告状態を持つレポートをエラーとして扱う必要があります<languageKeyword>false</languageKeyword>とき警告エラーとして処理するされません。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultServiceTypeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultServiceTypeHealthPolicy As ServiceTypeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.DefaultServiceTypeHealthPolicy : System.Fabric.Health.ServiceTypeHealthPolicy with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceTypeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または、既定では、サービスの種類のヘルスを評価するために使用する正常性ポリシーを設定します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />サービスの種類のポリシーが定義されていない場合は、サービスの種類の正常性を評価するために使用します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または異常な展開済みアプリケーションの許可される最大の割合を設定します。</para>
        </summary>
        <value>
          <para>許容される異常な展開済みアプリケーションの割合の最大値。 使用できる値は<see cref="T:System.Byte" />0 から 100 までの値。</para>
        </value>
        <remarks>
          <para>
            パーセンテージは、ことのできる正常なアプリケーションがエラーと見なされる前に配置されているアプリケーションの最大許容パーセンテージを表します。 これは、アプリケーションがクラスター内に展開される現在のノード数にわたって異常な展開済みアプリケーションの数で割ることによって計算されます。
            切り上げ計算が実行され、少数のノードに対する 1 つのエラーは許容されます。 既定のパーセンテージは 0 です。
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>指定した値は、0 から 100 までの整数値の範囲外でした。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeHealthPolicyMap As IDictionary(Of String, ServiceTypeHealthPolicy)" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeHealthPolicyMap : System.Collections.Generic.IDictionary&lt;string, System.Fabric.Health.ServiceTypeHealthPolicy&gt;" Usage="System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Fabric.Health.ServiceTypeHealthPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定を持つマップ<see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" />あたりサービス型の名前。 </para>
        </summary>
        <value>
          <para>サービスの種類の正常性ポリシー サービスの種類名ごとにマップします。</para>
        </value>
        <remarks>
          <para>マップ内のエントリは、指定されたサービスの種類ごとに既定のサービス型の正常性ポリシーを置き換えます。
            たとえば、アプリケーションでは、ステートレスなゲートウェイ サービスの種類とステートフル エンジン サービスの種類の両方を含む、ステートレスおよびステートフルなサービスの正常性ポリシー構成できる方法が異なります。
            サービスの種類ごとのポリシーには、サービスのヘルスをより細かく制御します。
            </para>
          <para>サービス型の名前のポリシーが指定されていない場合、<see cref="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />評価に使用します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthPolicy.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーションの正常性ポリシーの文字列表現を取得します。
            </summary>
        <returns>アプリケーションの正常性ポリシーの文字列形式。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>